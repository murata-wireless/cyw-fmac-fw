THE FOLLOWING NOTES APPLY ONCE THE YOCTO LINUX IMAGE IS BUILT AND ROOTFS IS POPULATED:
======================================================================================
Use "murata-master" sub-folder for module-specific CLM_BLOB file (CLM_BLOB filename includes Murata module designation). 
Note that the FMAC driver loads a specific NVRAM filename when coming up: "cyfmac"+<CYW number>+<-sdio or -pcie>+".clm_blob"
This means that for any Murata modules which share the same chipset, we can only have one CLM_BLOB file present in the default folder: "/lib/firmware/cypress".
The following module CLM_BLOB default files are included in this folder: 

The following table lists out the "md5sum" for all the CLM_BLOB files.
-----------------------------------------------------------------------------------
|   File Name                     |             md5sum               | Murata     |
|                                 |                                  | Regulatory |
|                                 |                                  | Certified  |
|---------------------------------|----------------------------------|------------|
| brcmfmac43012-sdio.1LV.clm_blob | 0fb69b76a77dc8d9af62eab1bca2ef69 |     Yes    |
| brcmfmac43455-sdio.1MW.clm_blob | dfb5979f56bc869302417a0df9798188 |     Yes    |
| brcmfmac43430-sdio.1DX.clm_blob | 966becd509a2fc8f30f27fa0dab4673e |     Yes    |
| brcmfmac43430-sdio.1FX.clm_blob | 966becd509a2fc8f30f27fa0dab4673e |     Yes    |
| brcmfmac43430-sdio.1LN.clm_blob | 966becd509a2fc8f30f27fa0dab4673e |     No     |
| brcmfmac43455-sdio.1HK.clm_blob | 4aafba3e50ac9756aebcb89b81979023 |     No     |
| brcmfmac43455-sdio.1LC.clm_blob | 4aafba3e50ac9756aebcb89b81979023 |     No     |
| brcmfmac4354-sdio.1BB.clm_blob  | 39404def8b34d793bd8aebf86fd9ede7 |     No     |
| brcmfmac4356-sdio.1CX.clm_blob  | f8611ec4459ebadf99bb999e5903df12 |     No     |
| brcmfmac4359-sdio.clm_blob      | 9fc5b48fd08e593e0339b2c0450e1337 |     No     |
| brcmfmac4373-sdio.clm_blob      | 05dea99d908cb7a1cb053d4ff2ad87be |     No     |
| brcmfmac54591-pcie.clm_blob     | 1a9db6fe74888d8e5be82d5747b6de6c |     No     |
-----------------------------------------------------------------------------------
