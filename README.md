############################################################################
* Author: Ubden
* GitHub URL: https://github.com/ubden/custom-esxi-iso-with-all-network-drivers-and-nvme-driver
* Esxi for 7.0.3
* Version: 1.0
############################################################################

* Prerequisites
* Only needs to be executed once, not every time an image is built
* Must be Administrator to execute prerequisites
*
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope LocalMachine
Install-Module -Name VMware.PowerCLI -SkipPublisherCheck

#############################################################################
