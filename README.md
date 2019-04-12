## Ubuntu18.04.01LTS fro the BUIDL bootcamp

Download the prebuilt Ubuntu18.04.01LTS image (Ubuntu18.04.01LTS.zip):
https://mega.nz/#F!JQ1S1KqT!nDiX3p9aCY-8DUvvmf-_mw?URt2WCAT

Unzip to use with Virtualbox.

username: buidl  
password: bootcamp

Installed and working: 
* git
* cloned github.com/justinmoon/digital-cash/
* pip
* venv
* digital-cash/requirements.txt
* docker
* docker-compose
* VisualStudio Code

---
To make a bootable image:  

in Windows with VirtualBox installed, run this in Command Prompt (cmd.exe) or PowerShell: 
`C:\Program_Files\Oracle\VirtualBox\VBoxManage.exe" clonehd --format RAW Ubuntu18.04.01LTS.vdi RAW_Image_to_disk.img`  

Burn the .img to a HDD/SSD/USB-drive with http://www.hddguru.com/software/HDD-Raw-Copy-Tool/.

---

in Linux bash:  
`VBoxManage clonehd --format RAW Ubuntu18.04.01LTS.vdi RAW_Image_to_disk.img`
