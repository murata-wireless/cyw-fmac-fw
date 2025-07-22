THE FOLLOWING NOTES APPLY ONCE THE YOCTO LINUX IMAGE IS BUILT AND ROOTFS IS POPULATED:
======================================================================================
Use "murata-master" sub-folder for module-specific CLM_BLOB file (CLM_BLOB filename includes Murata module designation). 
Note that the FMAC driver loads a specific NVRAM filename when coming up: "cyfmac"+<CYW number>+<-sdio or -pcie>+".clm_blob"
This means that for any Murata modules which share the same chipset, we can only have one CLM_BLOB file present in the default folder: "/lib/firmware/cypress".
The following module CLM_BLOB default files are included in this folder: 

The following table lists out the "md5sum" for all the CLM_BLOB files.
-----------------------------------------------------------------------------------------------
|   File Name                 	              |		md5sum	            	 | Murata     |
|                                             |				         | Regulatory |
|				              |               		         | Certified  |	
|---------------------------------------------|----------------------------------|------------|
| cyfmac43012-sdio.1LV.clm_blob               | 0fb69b76a77dc8d9af62eab1bca2ef69 |     Yes    |
| cyfmac43022-sdio.2GF.IndoorSTA.clm_blob     | 95afd53de635678a997f39b3e897d192 |     Yes    |
| cyfmac43022-sdio.2GF.OutdoorSTA.clm_blob    | fda7759da209942a3a9d0b6c27124d72 |     Yes    |
| cyfmac43022-sdio.2GF.IndoorAP.clm_blob      | b0d1d7cddcb32c4f9831a77b43fafe9f |     Yes    |
| cyfmac43022-sdio.2GF.OutdoorAP.clm_blob     | 8269c9fa74406876083b8086dd8e7b00 |     Yes    |
| cyfmac43455-sdio.1MW.clm_blob               | dfb5979f56bc869302417a0df9798188 |     Yes    |
| cyfmac43430-sdio.1DX.clm_blob               | 966becd509a2fc8f30f27fa0dab4673e |     Yes    |
| cyfmac43430-sdio.1FX.clm_blob               | 966becd509a2fc8f30f27fa0dab4673e |     Yes    |
| cyfmac43430-sdio.1LN.clm_blob               | 966becd509a2fc8f30f27fa0dab4673e |     No     |
| cyfmac43455-sdio.1HK.clm_blob               | 4aafba3e50ac9756aebcb89b81979023 |     No     |
| cyfmac43455-sdio.1LC.clm_blob               | 4aafba3e50ac9756aebcb89b81979023 |     No     |
| cyfmac4354-sdio.1BB.clm_blob                | 39404def8b34d793bd8aebf86fd9ede7 |     No     |
| cyfmac4359-sdio.1WZ.clm_blob	              | 9fc5b48fd08e593e0339b2c0450e1337 |     No     |
| cyfmac4373-sdio.2AE.clm_blob	              | 2ee452fab031bcf712af0c75929e428c |     Yes    |
| cyfmac4373-sdio.2BC.clm_blob	              | 2ee452fab031bcf712af0c75929e428c |     Yes    |
| cyfmac43439-sdio.1YN.clm_blob	              | 47fa101aac57c643a612754b6a05537a |     Yes    |
| cyfmac4356-pcie.1CX.clm_blob	              | f8611ec4459ebadf99bb999e5903df12 |     No     |
| cyfmac54591-pcie.1XA.clm_blob	              | 0eff4b59e0ffc5f1babc865bd05897c0 |     Yes    |
| cyfmac54591-sdio.2BZ.clm_blob	              | 0eff4b59e0ffc5f1babc865bd05897c0 |     Yes    |
| cyfmac55572-pcie.2EA.clm_blob_APIndoor      | 4eb6b49a24580d18ec011942f7b5a900 |     Yes    |
| cyfmac55572-pcie.2EA.clm_blob_APOutdoor     | 873855eb794413238528d46c0bea96ae |     Yes    |
| cyfmac55572-pcie.2EA.clm_blob_STAIndoor     | 469d3127e86d040ac7f82d42233bfff2 |     Yes    |
| cyfmac55572-pcie.2EA.clm_blob_STAOutdoor    | 7e004696f1d76827ae20bcb200d54aa1 |     Yes    |
| cyfmac55572-sdio.2EA.clm_blob_APIndoor      | 4eb6b49a24580d18ec011942f7b5a900 |     Yes    |
| cyfmac55572-sdio.2EA.clm_blob_APOutdoor     | 873855eb794413238528d46c0bea96ae |     Yes    |
| cyfmac55572-sdio.2EA.clm_blob_STAIndoor     | 469d3127e86d040ac7f82d42233bfff2 |     Yes    |
| cyfmac55572-sdio.2EA.clm_blob_STAOutdoor    | 7e004696f1d76827ae20bcb200d54aa1 |     Yes    |
| cyfmac55500-sdio.2FY.APIndoor.clm_blob      | a3d681833f8da8155dc6cde826c50182 |     Yes    |
| cyfmac55500-sdio.2FY.APOutdoor.clm_blob     | 5114e316022d89dde94a3f94334ca131 |     Yes    |
| cyfmac55500-sdio.2FY.STAIndoor.clm_blob     | b6664e361d86a8e09b04b44e07da6ef8 |     Yes    |
| cyfmac55500-sdio.2FY.STAOutdoor.clm_blob    | 136935f036f34bc3befc381bbb4f79d4 |     Yes    |
| cyfmac55500-sdio.2GY.APIndoor.clm_blob      | 239394f9f823ea2901996167a258dbb0 |     Yes    |
| cyfmac55500-sdio.2GY.APOutdoor.clm_blob     | 73dc62495bb4b5ee5a06107c283dc408 |     Yes    |
| cyfmac55500-sdio.2GY.STAIndoor.clm_blob     | 0c7054f32fabb9df2eb012573cbde349 |     Yes    |
| cyfmac55500-sdio.2GY.STAOutdoor.clm_blob    | 80842a030a2a29b71e5bfdf7d309a476 |     Yes    |
-----------------------------------------------------------------------------------------------
