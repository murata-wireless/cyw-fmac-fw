THE FOLLOWING NOTES APPLY ONCE THE YOCTO LINUX IMAGE IS BUILT AND ROOTFS IS POPULATED:
======================================================================================
Use "murata-master" sub-folder for module-specific CLM_BLOB file (FIRMWARE filename includes Murata module designation). 
Note that the FMAC driver loads a specific FIRMWARE filename when coming up: "cyfmac"+<CYW number>+<-sdio or -pcie>+".clm_blob"
This means that for any Murata modules which share the same chipset, we can only have one FIRMWARE file present in the default folder: "/lib/firmware/cypress".
The following module FIRMWARE default files are included in this folder: 

The following table lists out the "version" for all the FIRMWARE files.
-----------------------------------------
|   File Name         	|    version    |
|-----------------------|---------------|
| cyfmac43012-sdio.bin	| 13.10.271.273 |
| cyfmac43340-sdio.bin	| 6.10.190.91	|
| cyfmac43362-sdio.bin	| 5.90.261	|
| cyfmac4339-sdio.bin	| 6.37.39.131	|
| cyfmac43430-sdio.bin	| 7.45.98.118	|
| cyfmac43455-sdio.bin	| 7.45.234	|
| cyfmac4354-sdio.bin	| 7.35.349.112	|
| cyfmac4356-pcie.bin	| 7.35.180.208	|
| cyfmac4359-pcie.bin	| 9.40.130	|
| cyfmac4359-sdio.bin	| 9.40.129	|
| cyfmac4373-sdio.bin	| 13.10.246.261	|
| cyfmac54591-pcie.bin	| 13.35.253	|
-----------------------------------------
