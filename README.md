# HACKINTOSH Dell Precision 5520
# MacBook Pro 2017 14.3

  ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/desktop.webp)

  * Specifications
  ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/specs.webp)

**OpenCore Version** : [1.0.2](https://github.com/acidanthera/OpenCorePkg/releases)

 ### Bootloader
  * [reFind](https://www.rodsbooks.com/refind/)
  * ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/reFindBootManager.webp)
  **TRIPLE BOOT** : Ventura 13.6.7 / Ubuntu 22.04 / Windows 11

## Configuration

| Model     | MacBook Pro 2017  14.3      | Version        | Ventura 13.6        |
| :-------- | :---------------------------| :------------- | :------------------ |
| Processor | Intel Core i7-7820HQ        | Graphics       | Intel UHD 630       |
| Memory    | 16Go x2                     | Storage        | SamSung SSD 970EVO  |
| Mobo      | DeLL                        | BIOS revision  | DeLL Bios           |
| Network   | intel AC 8265               | Audio          | Realtek layout 42   | 
| Display   | DeLL LCD                    | Monitor        | LCD integrated      |

 ### Working
 * GPU: Intel(R) UHD Graphics 630✅
 * Network Wifi: AC8265 AirportItlwm ✅
 * Bluetooth: IntelBluetoothFirmware ✅
 * Audio：spkear & mic working ✅
 * Input：keyboard mouse ✅
 * USB port：Working ✅ (Mapped with [USBTOOLBox](https://github.com/USBToolBox/tool))
 * Sleep/Wake：working ✅
 
 
 ### Post installation
  * I generated random Platform ID, use [GENSMBIOS](https://github.com/corpnewt/GenSMBIOS) or [OCAT](https://github.com/ic005k/OCAuxiliaryTools/releases) to generate your own Serial/UUID/MLB,
   
 ## Credit

 - Thanks to [Dortania Team](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites) and [OpenCoreTeam](https://github.com/acidanthera/OpenCorePkg)
