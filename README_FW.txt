THE FOLLOWING NOTES APPLY ONCE THE YOCTO LINUX IMAGE IS BUILT AND ROOTFS IS POPULATED:
======================================================================================

Please refer to the "FMAC_FW_Versions.xlsx" file present in the Murata GitHub for the
production FW file links for various FMAC releases.
https://github.com/romit-murata/cyw-fmac-fw/blob/indrik/FMAC_FW_Versions.xlsx

The FW files are hosted on the Infineon GitHub, except for the 2AE-USB and 2BC-USB FW files.
These are hosted by Murata in the Murata GitHub, because the USB FW contain Murata specific
NVRAM files integrated.

The "FMAC_FW_Versions.xlsx" file links the correct files.

Place the downloaded production FW file in "/lib/firmware/cypress" folder before loading
the driver.

