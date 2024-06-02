**Notes-**

-  [Recommended FW for lime »](https://t.me/Hac4us_Screenshots/342)
-  [Recommended FW for citrus » ](https://t.me/Hac4us_Screenshots/341)
-  Clean Flash Mandatory

**Prerequisite-**

1. Boot
2. Vendor_Boot
3. ROM

**How To Flash-**

1. Reboot To Fastboot by pressing
2. Vol Down + Power Button
3. Now Open CMD or Terminal in Your PC and connect your phone via USB
4. Now type

> fastboot flash boot boot.img

5. Then Type

> fastboot flash vendor_boot vendor_boot\*.img

6.After Flashing now Reboot into Recovery by pressing

> Volume Up + Power Button

7. After booting into Recovery click on Factory Reset and then do Format data / Factory reset

8. Select Apply Update using Sideload

9. Install the ROM by typing

> adb sideload GenesisOS-Official\*.zip

10. After Sideload Press NO to

11. Reboot To Recovery

12. Now Reboot to System

Note: \* Name varies from build to build
