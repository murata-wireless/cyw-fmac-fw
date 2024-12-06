THE FOLLOWING NOTES APPLY ONCE THE YOCTO LINUX IMAGE IS BUILT AND ROOTFS IS POPULATED:
======================================================================================
Use "murata-master" sub-folder for module-specific CLM_BLOB file (FIRMWARE filename includes Murata module designation). 
Note that the FMAC driver loads a specific FIRMWARE filename when coming up: "cyfmac"+<CYW number>+<-sdio or -pcie>+".clm_blob"
This means that for any Murata modules which share the same chipset, we can only have one FIRMWARE file present in the default folder: "/lib/firmware/cypress".
The following module FIRMWARE default files are included in this folder: 

The following table lists out the "version" for all the FIRMWARE files.
------------------------------------------
|   File Name         	  |    version    |
|-------------------------|---------------|
| cyfmac43012-sdio.bin	  | 13.10.271.314 |
| cyfmac43340-sdio.bin	  | 6.10.190.91	  |
| cyfmac43362-sdio.bin	  | 5.90.261	  |
| cyfmac4339-sdio.bin	  | 6.37.39.131	  |
| cyfmac43430-sdio.bin	  | 7.45.98.125	  |
| cyfmac43439-sdio.bin	  | 7.95.75       |
| cyfmac43455-sdio.bin	  | 7.45.265	  |
| cyfmac4354-sdio.bin	  | 7.35.349.117  |
| cyfmac4356-pcie.bin	  | 7.35.180.212  |
| cyfmac4359-pcie.bin	  | 9.40.130	  |
| cyfmac4359-sdio.bin	  | 9.40.129	  |
| cyfmac4373-sdio.2BC.bin | 13.10.246.334 |
| cyfmac4373-sdio.2AE.bin | 13.10.246.334 |
| cyfmac4373-usb.2BC.bin  | 13.10.246.334 |
| cyfmac4373-usb.2AE.bin  | 13.10.246.334 |
| cyfmac54591-sdio.bin	  | 13.35.327	  |
| cyfmac54591-pcie.bin	  | 13.35.327	  |
| cyfmac55500-sdio.trxse  | 28.10.387.10  |
| cyfmac55572-sdio.trxse  | 18.53.284.17  |
| cyfmac55572-pcie.trxse  | 18.53.284.17  |
| cyfmac43022-sdio.trxs   | 13.34.107.121 |
-------------------------------------------

Note: Same firmware file (cyfmac54591-sdio.bin) is used for 2BZ. 2BZ is based out of IFX chipset 54590.
