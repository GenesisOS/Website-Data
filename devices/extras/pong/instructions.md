### Notes
- Genesis Recovery Recommended
- Clean flash mandatory

### Prerequisite
- Recovery
- VendorBoot
- Boot
- Dtbo
- ROM

### How To Flash
1. Reboot To Fastboot by pressing
>Vol Down + Power Button

2. Now Open CMD or Terminal in Your PC and connect your phone via USB
3. Now type 
>fastboot flash boot boot.img

4. Then
>fastboot flash vendor_boot vendor_boot.img

5. Next
>fastboot flash dtbo dtbo.img

6. After that
>fastboot flash recovery_a recovery.img
>fastboot flash recovery_b recovery.img

7. After Flashing now Reboot into Recovery by pressing
>Volume Up + Power Button

8. After booting into Recovery click on Factory Reset and then do Format data / Factory reset
9. Now Select Apply Update using Sideload
10. Install the ROM by typing
>adb sideload GenesisOS-Official*.zip

11. After Sideload Press NO to "Reboot To Recovery" popup
12. Now Reboot to System

**P.S: * Name varies from build to build**
