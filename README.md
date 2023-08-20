# Dell-Precision5520-hackintosh

  ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/desktop1.jpeg)


**OpenCore Version** : [0.93](https://github.com/acidanthera/OpenCorePkg/releases)

 ### Bootloader
  * [reFind](https://www.rodsbooks.com/refind/)
  ![](https://github.com/GUNNERSx/Dell-Precision5520-hackintosh/blob/main/reFind.jpg)
  **TRIPPLE BOOT** : Ventura 13.3 / Windows 11 / Ubuntu 22.04

## Configuration

| Model     |  Precision/MacBookPro15,3    | Version        | Ventura 13.3        |
| :-------- | :--------------------------- | :------------- | :------------------ |
| Processor | Intel Core i7-7820HQ         | Graphics       | UHD Graphics 630    |
| Memory    | DDR4 16GB x2                 | Storage        | Samsung 970EVO 512GB|
| Audio     | Realtek ALC298               | WiFi/Bluetooth | intel 8265          |
| Display   | DeLL LCD 1980x1024           | Monitor        |  FHD                |

 ### Working
 * iGPU：working.
 * Wireless Card(intel Wireless 8265 )：WiFi&BT working.
 * Audio：spkear & mic working (layout-id 40)
 * Camera：working.
 * Input：keyboard & touchpad working.
 * HDMI Port：working.
 * USB port：Type-A port x 2 (Max 5 Gbps) and Type-C port x 1 (Max 10 Gbps)
 * Brightness Controll：Yes with Fn+B or Fn+S.
 * Sleep/Wake：working.
 * SDCard Reader：working.
 
 ### Post installation
  * Use [GENSMBIOS](https://github.com/corpnewt/GenSMBIOS) or [OCAT](https://github.com/ic005k/OCAuxiliaryTools/releases) to generate your own Serial/UUID/MLB
   
 ## Credit

 - Thank, [mistzzt](https://github.com/mistzzt/XPS-9560-OpenCore)
