# HACKINTOSH Dell Precision 5520
# Hackintosh MacBook Pro 2017

  ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/desktop.webp)

  * Specification
  ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/specs.webp)

**OpenCore Version** : [1.0.2](https://github.com/acidanthera/OpenCorePkg/releases)

 ### Bootloader
  * [reFind](https://www.rodsbooks.com/refind/)
  * ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/reFindBootManager.webp)
  **TRIPLE BOOT** : Ventura 13.6.7 / Windows 11 / Linux Mint

## Configuration

| Model     | iMac 19,1                   | Version        | Ventura 13.7        |
| :-------- | :---------------------------| :------------- | :------------------ |
| Processor | Intel Core i7-9700K         | Graphics       | Sapphire Rx580 8Go  |
| Memory    | Gskill 2667MHz DDR4 8GB x2  | Storage        | WD_Black SN770      |
| Mobo      | MSI B360M PRo VD            | BIOS revision  | AMI BIOS 7B53v1C    |
| Network   | RTL8111H Gigabit            | Audio          | Realtek ALC887      | 
| Display   | BenQ                        | Monitor 144Hz  | Zowie XL2411P  24"  |

 ### Working
 * GPU: [Sapphire NITRO+ RX 580 Special Edition](https://www.techpowerup.com/gpu-specs/sapphire-nitro-rx-580-special-edition.b4912) ✅
 * Wifi 6 AX210 AirportItlwm ✅
 * Bluetooth IntelBluetoothFirmware ✅
 * Network: RTL8111H Gigabit ✅ (with [Realtek RTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X))
 * Audio：spkear & mic working ✅
 * Input：keyboard mouse ✅
 * USB port：Working ✅ (Mapped with [USBTOOLBox](https://github.com/USBToolBox/tool))
 * Sleep/Wake：working ✅ (Have to turn off display and turn it back ON after system wake UP)
 
 
 ### Post installation
  * I generated random Platform ID, use [GENSMBIOS](https://github.com/corpnewt/GenSMBIOS) or [OCAT](https://github.com/ic005k/OCAuxiliaryTools/releases) to generate your own Serial/UUID/MLB,
  * ACPI are generate with [Corpnewt SSDTime](https://github.com/corpnewt/SSDTTime) under Windows11 manually, default from [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#acpi) 
   are in EFI/OC/ACPI/Back
   
 ## Credit

 - Thanks to [Matcha-xiaobin](https://github.com/Matcha-xiaobin/EFI-B360m_d2v_OpenCore_dvi_uhd630) for DVI patch!
