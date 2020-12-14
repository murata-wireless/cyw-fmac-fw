THE FOLLOWING NOTES APPLY ONCE THE YOCTO LINUX IMAGE IS BUILT AND ROOTFS IS POPULATED:
======================================================================================
Use "murata-master" sub-folder for module-specific CLM_BLOB file (FIRMWARE filename includes Murata module designation). 
Note that the FMAC driver loads a specific FIRMWARE filename when coming up: "brcmfmac"+<CYW number>+<-sdio or -pcie>+".clm_blob"
This means that for any Murata modules which share the same chipset, we can only have one FIRMWARE file present in the default folder: "/lib/firmware/cypress".
The following module FIRMWARE default files are included in this folder: 

The following table lists out the "version" for all the FIRMWARE files.
------------------------------------------
|       File Name    	 |    version    |
|------------------------|---------------|
| brcmfmac43012-sdio.bin | 13.10.271.227 |
| brcmfmac43340-sdio.bin | 6.10.190.78	 |
| brcmfmac4336-sdio.bin	 | 5.90.254	 |
| brcmfmac4339-sdio.bin	 | 6.37.39.113	 |
| brcmfmac43430-sdio.bin | 7.45.98.94	 |
| brcmfmac43455-sdio.bin | 7.45.198	 |
| brcmfmac4354-sdio.bin	 | 7.35.349.86	 |
| brcmfmac4356-pcie.bin	 | 7.35.180.197	 |
| brcmfmac4359-pcie.bin	 | 9.40.124	 |
| brcmfmac4359-sdio.bin	 | 9.40.123	 |
| brcmfmac4373-sdio.bin	 | 13.10.246.232 |
| brcmfmac54591-pcie.bin | 13.10.246.210 |
------------------------------------------
