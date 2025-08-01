THE FOLLOWING NOTES APPLY ONCE THE YOCTO LINUX IMAGE IS BUILT AND ROOTFS IS POPULATED:
======================================================================================

Please refer to the table below, or the "FMAC_FW_Versions.xlsx" file present in
the Murata GitHub for the production FW file links for various FMAC releases.
- https://github.com/romit-murata/cyw-fmac-fw/blob/kraken/FMAC_FW_Versions.xlsx

The FW files are hosted on the Infineon GitHub, except for the 2AE-USB and 2BC-USB FW files.
These are hosted by Murata in the Murata GitHub, because the USB FW contain Murata specific
NVRAM files integrated.

The "FMAC_FW_Versions.xlsx" file links the correct files.

Place the downloaded production FW file in "/lib/firmware/cypress" folder before loading
the driver.

1LV (CYW43012): 
---------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac43012-sdio.bin
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac43012-sdio.bin
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2024_0514/firmware/cyfmac43012-sdio.bin
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_1128/firmware/cyfmac43012-sdio.bin
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac43012-sdio.bin
Fafnir: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0222/firmware/cyfmac43012-sdio.bin
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43012-sdio.bin
Drogon: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_511/firmware/cyfmac43012-sdio.bin
Cynder: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2021_1020/firmware/cyfmac43012-sdio.bin
Baragon: https://community.infineon.com/t5/Wi-Fi-Bluetooth-for-Linux/Cypress-Linux-WiFi-Driver-Release-FMAC-2021-05-27/td-p/277394

2GF (CYW43022):
---------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac43022-sdio.trxs
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac43022-sdio.trxs
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2024_0514/firmware/cyfmac43022-sdio.trxs

1DX/1FX (CYW43430):
-------------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43430-sdio.bin
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43430-sdio.bin 
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43430-sdio.bin
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43430-sdio.bin
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43430-sdio.bin
Fafnir: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43430-sdio.bin
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43430-sdio.bin
Drogon: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_511/firmware/cyfmac43430-sdio.bin
Cynder: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2021_1020/firmware/cyfmac43430-sdio.bin
Baragon: https://community.infineon.com/t5/Wi-Fi-Bluetooth-for-Linux/Cypress-Linux-WiFi-Driver-Release-FMAC-2021-05-27/td-p/277394

1YN (CYW43439):
---------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac43439-sdio.bin
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac43439-sdio.bin
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2024_0514/firmware/cyfmac43439-sdio.bin
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_1128/firmware/cyfmac43439-sdio.bin
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac43439-sdio.bin
Fafnir: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0222/firmware/cyfmac43439-sdio.bin
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43439-sdio.bin
Drogon: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_511/firmware/cyfmac43439-sdio.bin
Cynder: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2021_1020/firmware/cyfmac43439-sdio.bin
Baragon: https://community.infineon.com/t5/Wi-Fi-Bluetooth-for-Linux/Cypress-Linux-WiFi-Driver-Release-FMAC-2021-05-27/td-p/277394

1MW (CYW43455):
---------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac43455-sdio.bin
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac43455-sdio.bin
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac43455-sdio.bin
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac43455-sdio.bin
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac43455-sdio.bin
Fafnir: https://community.infineon.com/gfawx74859/attachments/gfawx74859/broadcom-linux-partner-module-support-portaltkb-board/28/2/cypress-fmac-v5.15.58-20221223.zip
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac43455-sdio.bin)
Drogon: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_511/firmware/cyfmac43455-sdio.bin
Cynder: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2021_1020/firmware/cyfmac43455-sdio.bin
Baragon: https://community.infineon.com/t5/Wi-Fi-Bluetooth-for-Linux/Cypress-Linux-WiFi-Driver-Release-FMAC-2021-05-27/td-p/277394

2AE-SDIO (CYW4373E):
--------------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac4373-sdio.industrial.bin
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac4373-sdio.industrial.bin
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2024_0514/firmware/cyfmac4373-sdio.industrial.bin
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_1128/firmware/cyfmac4373-sdio.industrial.bin
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac4373-sdio.industrial.bin
Fafnir: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0222/firmware/cyfmac4373-sdio.industrial.bin
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac4373-sdio.industrial.bin
Drogon: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_511/firmware/cyfmac4373-sdio.industrial.bin
Cynder: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2021_1020/firmware/cyfmac4373-sdio.industrial.bin
Baragon: https://community.infineon.com/t5/Wi-Fi-Bluetooth-for-Linux/Cypress-Linux-WiFi-Driver-Release-FMAC-2021-05-27/td-p/277394

2BC-SDIO (CYW4373):
-------------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac4373-sdio.bin
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac4373-sdio.bin
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2024_0514/firmware/cyfmac4373-sdio.bin
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_1128/firmware/cyfmac4373-sdio.bin
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac4373-sdio.bin
Fafnir: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0222/firmware/cyfmac4373-sdio.bin
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac4373-sdio.bin
Drogon: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_511/firmware/cyfmac4373-sdio.bin
Cynder: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2021_1020/firmware/cyfmac4373-sdio.bin

2AE-USB (CYW4373E):
-------------------
Kraken: https://github.com/murata-wireless/cyw-fmac-fw/blob/kraken/cyfmac4373-usb.2AE.bin
Jaculus: https://github.com/murata-wireless/cyw-fmac-fw/blob/jaculus/cyfmac4373-usb.2AE.bin
Indrik: https://github.com/murata-wireless/cyw-fmac-fw/blob/indrik/cyfmac4373-usb.2AE.bin
Hedorah: https://github.com/murata-wireless/cyw-fmac-fw/blob/hedorah/cyfmac4373-usb.2AE.bin
Godzilla: https://github.com/murata-wireless/cyw-fmac-fw/blob/godzilla/cyfmac4373-usb.2AE.bin
Fafnir: https://github.com/murata-wireless/cyw-fmac-fw/blob/fafnir/cyfmac4373-usb.2AE.bin
Ebirah: https://github.com/murata-wireless/cyw-fmac-fw/blob/ebirah/cyfmac4373-usb.2AE.bin
Drogon: https://github.com/murata-wireless/cyw-fmac-fw/blob/drogon/cyfmac4373-usb.2AE.bin

2BC-USB (CYW4373):
------------------
Kraken: https://github.com/murata-wireless/cyw-fmac-fw/blob/kraken/cyfmac4373-usb.2BC.bin
Jaculus: https://github.com/murata-wireless/cyw-fmac-fw/blob/jaculus/cyfmac4373-usb.2BC.bin
Indrik: https://github.com/murata-wireless/cyw-fmac-fw/blob/indrik/cyfmac4373-usb.2BC.bin
Hedorah: https://github.com/murata-wireless/cyw-fmac-fw/blob/hedorah/cyfmac4373-usb.2BC.bin
Godzilla: https://github.com/murata-wireless/cyw-fmac-fw/blob/godzilla/cyfmac4373-usb.2BC.bin
Fafnir: https://github.com/murata-wireless/cyw-fmac-fw/blob/fafnir/cyfmac4373-usb.2BC.bin
Ebirah: https://github.com/murata-wireless/cyw-fmac-fw/blob/ebirah/cyfmac4373-usb.2BC.bin
Drogon: https://github.com/murata-wireless/cyw-fmac-fw/blob/drogon/cyfmac4373-usb.2BC.bin
Cynder: https://github.com/murata-wireless/cyw-fmac-fw/blob/cynder/cyfmac4373-usb.2BC.bin

1XA/2BA (CYW54591):
-------------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac54591-pcie.bin
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac54591-pcie.bin
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2024_0514/firmware/cyfmac54591-pcie.bin
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_1128/firmware/cyfmac54591-pcie.bin
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac54591-pcie.bin
Fafnir: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0222/firmware/cyfmac54591-pcie.bin
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac54591-pcie.bin
Drogon: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_511/firmware/cyfmac54591-pcie.bin
Cynder: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2021_1020/firmware/cyfmac54591-pcie.bin
Baragon: https://community.infineon.com/t5/Wi-Fi-Bluetooth-for-Linux/Cypress-Linux-WiFi-Driver-Release-FMAC-2021-05-27/td-p/277394

2BZ (CYW54590):
---------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac54591-sdio.bin
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac54591-sdio.bin
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2024_0514/firmware/cyfmac54591-sdio.bin
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_1128/firmware/cyfmac54591-sdio.bin
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac54591-sdio.bin
Fafnir: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0222/firmware/cyfmac54591-sdio.bin
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac54591-sdio.bin
Drogon: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_511/firmware/cyfmac54591-sdio.bin
Cynder: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2021_1020/firmware/cyfmac54591-sdio.bin
Baragon: https://community.infineon.com/t5/Wi-Fi-Bluetooth-for-Linux/Cypress-Linux-WiFi-Driver-Release-FMAC-2021-05-27/td-p/277394

2FY (CYW55513):
---------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac55500-sdio.trxse
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac55500-sdio.trxse

2EA-PCIe (CYW55573):
--------------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac55572-pcie.trxse
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac55572-pcie.trxse
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2024_0514/firmware/cyfmac55572-pcie.trxse
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_1128/firmware/cyfmac55572-pcie.trxse
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac55572-pcie.trxse
Fafnir: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0222/firmware/cyfmac55572-pcie.trxse 
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac55572-pcie.trxse

2EA-SDIO (CYW55573):
--------------------
Kraken: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.110-2025_0602/firmware/cyfmac55572-sdio.trxse
Jaculus: https://github.com/Infineon/ifx-linux-firmware/blob/release-v6.1.97-2024_1115/firmware/cyfmac55572-sdio.trxse
Indrik: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2024_0514/firmware/cyfmac55572-sdio.trxse
Hedorah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_1128/firmware/cyfmac55572-sdio.trxse
Godzilla: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0901/firmware/cyfmac55572-sdio.trxse
Fafnir: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.15.58-2023_0222/firmware/cyfmac55572-sdio.trxse
Ebirah: https://github.com/Infineon/ifx-linux-firmware/blob/release-v5.10.9-2022_0909/firmware/cyfmac55572-sdio.trxse

Note:
-----
1. For 2AE-SDIO, rename the "cyfmac4373-sdio.industrial.bin" FW file to "cyfmac4373-sdio.bin" before using.
2. For 2AE-USB, rename the "cyfmac4373-usb.2AE.bin" FW file to "cyfmac4373.bin" before using.
3. For 2BC-USB, rename the "cyfmac4373-usb.2BC.bin" FW file to "cyfmac4373.bin" before using.
4. Same firmware file (cyfmac54591-sdio.bin) is used for 2BZ and 1XA. 2BZ is based out of IFX chipset 54590.
