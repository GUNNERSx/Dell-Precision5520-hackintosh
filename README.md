# HACKINTOSH Dell Precision 5520
# MacBook Pro 2017

  ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/desktop.webp)

  * Specification
  ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/specs.webp)

**OpenCore Version** : [1.0.2](https://github.com/acidanthera/OpenCorePkg/releases)

 ### Bootloader
  * [reFind](https://www.rodsbooks.com/refind/)
  * ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/reFindBootManager.webp)
  **TRIPLE BOOT** : Ventura 13.6.7 / Windows 11 / Ubuntu 22.04

## Configuration

| Model     | MacBook Pro 2017  14.3      | Version        | Ventura 13.6        |
| :-------- | :---------------------------| :------------- | :------------------ |
| Processor | Intel Core i7-7820HQ        | Graphics       | Intel UHD Graphics 630 |
| Memory    | 16 Go x2                    | Storage        | Samsung SSD 970     |
| Mobo      | DeLl                        | BIOS revision  | DeLL Bios           |
| Network   | intel AC 8265               | Audio          | Realtek             | 
| Display   | Dell LCD                    | Monitor        | LCD integrated      |

 ### Working
 * GPU: Intel(R) UHD Graphics 630✅
 * Wifi: AirportItlwm ✅
 * Bluetooth IntelBluetoothFirmware ✅
 * Network:  ✅ 
 * Audio：spkear & mic working ✅
 * Input：keyboard mouse ✅
 * USB port：Working ✅ (Mapped with [USBTOOLBox](https://github.com/USBToolBox/tool))
 * Sleep/Wake：working ✅
 
 
 ### Post installation
  * I generated random Platform ID, use [GENSMBIOS](https://github.com/corpnewt/GenSMBIOS) or [OCAT](https://github.com/ic005k/OCAuxiliaryTools/releases) to generate your own Serial/UUID/MLB,
   
 ## Credit

 - Thanks to [Dortania Team](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html#prerequisites) and [OpenCoreTeam](https://github.com/acidanthera/OpenCorePkg)
