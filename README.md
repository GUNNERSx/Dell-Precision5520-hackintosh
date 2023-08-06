# HACKINTOSH-MSI-B360M
[MSI B360M PRo VD](https://www.msi.com/Motherboard/B360M-PRO-VD/Specification) DVI_UHD630_i7-9700K
# Hackintosh iMac 19,1 2020

  ![](https://github.com/GUNNERSx/HACKINTOSH-MSI-B360M_DVI_UHD630_i7-9700K/blob/main/Pic.jpg)

  * Specification
  ![](https://github.com/GUNNERSx/HACKINTOSH-MSI-B360M_DVI_UHD630_i7-9700K/blob/main/specs.jpg)

**OpenCore Version** : [0.93](https://github.com/acidanthera/OpenCorePkg/releases)

 ### Bootloader
  * [reFind](https://www.rodsbooks.com/refind/)
  **DUAL BOOT** : Ventura 13.5 / Windows 11 

## Configuration

| Model     | iMac 19,1                   | Version        | Ventura 13.5        |
| :-------- | :---------------------------| :------------- | :------------------ |
| Processor | Intel Core i7-9700K         | Graphics       | UHD Graphics 630    |
| Memory    | Gskill 2667MHz DDR4 8GB x2  | Storage        | WD_Black SN770      |
| Mobo      | MSI B360M PRo VD            | BIOS revision  | AMI BIOS 7B53v1C    |
| Network   | RTL8111H Gigabit            | Audio          | Realtek ALC887      | 
| Display   | BenQ                        | Monitor        | Zowie XL2411P       |

 ### Working
 * iGPU：working.
 * Wireless Card(intel Wireless 8265 )：WiFi&BT working.
 * Audio：spkear & mic working.
 * Input：keyboard & touchpad working.
 * HDMI Port：working.
 * USB port：Working
 * Brightness Controll：Working
 * Sleep/Wake：working (Have to turn off display and turn it back ON after system wake UP)
 
 ### Post installation
  * I generate random Platform ID, use [GENSMBIOS](https://github.com/corpnewt/GenSMBIOS) or [OCAT](https://github.com/ic005k/OCAuxiliaryTools/releases) to generate your own Serial/UUID/MLB
   
 ## Credit

 - Thanks to [Matcha-xiaobin](https://github.com/Matcha-xiaobin/EFI-B360m_d2v_OpenCore_dvi_uhd630) for DVI patch!
