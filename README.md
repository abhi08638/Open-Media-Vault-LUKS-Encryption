# Open-Media-Vault-LUKS-Encryption
This repo describes the process of creating an encrypted Drive in Open Media Vault 7 using LUKS and setting up crypttab to auto-unlock the drive on boot

NOTE: There are other guides out there that describe encrypting the boot drive, SWAP, and /tmp. My use case is only to protect the drives in case of theft. You can move /tmp to a tmpfs in RAM using the Write Cache plugin. 

Download the excel file to view the instructions as well as generate the commands required to run. 

"Drive Encryption Steps" covers encrpyting a drive with LUKS and then having it auto-unlock on boot
"File Migration Commands" covers migrating files from one drive to another (in this case migrating files from an encrpyted drive to an encrypted drive)

FULL DISCLAIMER: 
DO NOT delete your original files without fully testing your system first. Always maintain a backup of your data in case something goes wrong. 
