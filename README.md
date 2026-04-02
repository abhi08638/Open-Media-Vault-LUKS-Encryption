# Open-Media-Vault-LUKS-Encryption
This repo describes the process of creating an encrypted Drive in Open Media Vault 7 using LUKS and setting up crypttab to auto-unlock the drive on boot

NOTE: There are other guides out there that describe encrypting the boot drive, SWAP, and /tmp. My use case is only to protect the drives in case of theft. You can move /tmp to a tmpfs in RAM using the Write Cache plugin. 

