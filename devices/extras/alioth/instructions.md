### Notes
- Use latest Regional FW
- Use Genesis Recovery
- Clean flash mandatory

### Prerequisite
- Boot
- VendorBoot
- ROM

### How To Flash
1. Reboot To Fastboot by pressing
>Vol Down + Power Button

2. Now Open CMD or Terminal in Your PC and connect your phone via USB
3. Now type 
>fastboot flash boot boot.img

4. Then Type
>fastboot flash vendor_boot vendor_boot*.img

5. After Flashing now Reboot into Recovery by pressing
>Volume Up + Power Button

6. After booting into Recovery click on Factory Reset and then do Format data / Factory reset
7. Now Select Apply Update using Sideload
8. Install the ROM by typing
>adb sideload GenesisOS-Official*.zip

9. After Sideload Press NO to "Reboot To Recovery" popup
10. Now Reboot to System

**P.S: * Name varies from build to build**