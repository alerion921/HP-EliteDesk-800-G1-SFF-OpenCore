# HP-EliteDesk-800-G1-SFF-OpenCore
Successfully Installed OSX Ventura 13.2


Install EFI (The EFI i used on my USB drive to install OSX Monterey)
Post-Install EFI (The EFI i replaced "install EFI" with after the first boot after completed installation)

English is not my native language so that would be why some of the things i write come of as weird but feel free to ask questions.

Wifi and Bluetooth is not in use at my system so therefor there is no patches or kexts added for that so if you need that you will have to add them yourself, 
also there is an issue with HD4600 only being at 8mb since support was dropped in Ventura so for this i used OCLP (OpenCore Legacy Patcher) it added some
root patches but you will need to disable SIP and AMFI for this (Should be dont automaticly in the Post-Install EFI) and this works smooth and all VRAM is now back.

Feel free to ask me questions by adding an issue or suggestion.
