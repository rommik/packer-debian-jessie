## Requirements
You will need to install and configure 

1) Packer.io (https://www.packer.io/) 
2) Builders
    a) VirtualBox (https://www.virtualbox.org/) - Windows User Note: If you have docker installed on your PC, you will need to disable
    the Hyper-V temporarely (in Program and Features, Windows Features). Otherwise, VirtualBox cannot run x64 guest OS.

## DEBUG Build 
packer build -on-error=ask debian.json

##Root
Root password is qwerty. Don't forget to update the preseed configuration file.