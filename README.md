# HP-Pavilion-x360-cd0080tu-hackintosh


## Configuration

| Specifications      | Detail                       |
| ------------------- | ---------------------------- |
| CPU                 | Intel(R) Core(TM) i5-8250U   |
| Integrated Graphics | Intel UHD Graphics 620       |
| Wireless Card       | Dual Band Wireless-AC 3165 Plus Bluetooth      |




## MacOS Versions Supported:

- macOS Monterey 12.0.1 (21A559)


## Config & SSDT & Kexts :

<details>  
<summary> APCI：</summary> 

- `SSDT-ADP1`
- `SSDT-ALSD`
- `SSDT-DMAC`
- `SSDT-EC-USBX`
- `SSDT-GPI0_GPEN`
- `SSDT-GPRW`
- `SSDT-I2C`
- `SSDT-MCHC_SBUS`
- `SSDT-PLUG`
- `SSDT-PNLF`
- `SSDT-SRAM`

</details> 

<details>  
<summary> Kexts：</summary>
 
- `Lilu.kext`
- `VirtualSMC.kext
- `WhateverGreen.kext`
- `AppleALC.kext`
- `VoodooPS2Controller.kext`
- `BrightnessKeys.kext`
- `VoodooI2C.kext`
- `AirportItlwm.kext`
- `BlueToolFixup.kext`(if you isntall mac os Monterey use this kext and delete `BluetoothInjector.kext`)
- `IntelBluetoothFirmware.kext` 
- `IntelBluetoothInjector.kext` (end wotking on mac os Monterey)
- `USBInjectAll.kext`
 
</details> 

## What is Working?

- [x] Native CPU Power Management
- [x] Sleep/Wake
- [x] Intel Graphics
- [x] Audio
- [x] Trackpad (gestures)
- [x] USB 3.0
- [x] Battery Management 
- [x] Brightness
- [x] Built-in camera
- [x] Built-in mic
- [x] Line-in mic
- [x] Bluetooth Intel
- [x] Intel wireless

 

## Screen Shot


![Screen Shot 1400-07-26 at 11 43 04 PM](https://user-images.githubusercontent.com/35195176/137881878-c3642bed-6b50-4f89-bdc7-ae033bf90e7b.png)

![Screen Shot 1400-07-30 at 7 39 27 PM](https://user-images.githubusercontent.com/35195176/138489029-87ecd7e3-fbdc-4b88-9125-4702fc2470d9.png)





## Thanks：


- [@hackintoshlife](https://github.com/Hackintoshlifeit) best gp for hackintosh


- [@acidanthera](https://github.com/acidanthera/OpenCorePkg) for OpenCorePkg 


- [@apple](https://www.apple.com/) created macos 


- [@Baio1977](https://github.com/Baio1977) He made efi folder and ssdt

 
- [@zxystd](https://github.com/OpenIntelWireless/itlwm) created kexts of wifi and bluetooth  
