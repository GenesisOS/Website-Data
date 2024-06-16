### Notes
- Genesis Recovery Recommended
- Clean flash mandatory

### Prerequisite
- Recovery
- VendorBoot
- Boot
- ROM

### How To Flash
1. Reboot To Fastboot by pressing
>Vol Down + Power Button

2. Now Open CMD or Terminal in Your PC and connect your phone via USB
3. Now type 
>fastboot flash boot boot.img

4. Then
>fastboot flash vendor_boot vendor_boot.img

5. After that
>fastboot flash recovery recovery.img

6. After Flashing now Reboot into Recovery by pressing
>Volume Up + Power Button

7. After booting into Recovery click on Factory Reset and then do Format data / Factory reset
8. Now Select Apply Update using Sideload
9. Install the ROM by typing
>adb sideload GenesisOS-Official*.zip

10. After Sideload Press NO to "Reboot To Recovery" popup
11. Now Reboot to System

**P.S: * Name varies from build to build**
