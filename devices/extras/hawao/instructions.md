### Notes  
- Clean Flash Mandatory

### Prerequisite
- DTBO
- VendorBoot
- Boot
- [Copy_Partion.zip](https://t.me/GenesisOSChat/45506/56342)
- ROM

### How To Flash
1. Reboot To Fastboot by pressing 
>Vol Down + Power Button

2. Flash the downloaded image files to your device by typing:
>fastboot flash dtbo dtbo.img
fastboot flash vendor_boot vendor_boot.img

3. Flash recovery onto your device
>fastboot flash boot boot.img

4. Reboot to Recovery 
>fastboot reboot recovery

5. On the device, select “Apply Update”, then “Apply from ADB” to begin the sideload. 
6. On the host machine, sideload the package using
>adb -d sideload copy-partitions-20220613-signed.zip

7. Now Tap On Advanced and then press Reboot To Recovery
8. After rebooting into Recovery click on Factory Reset and then do Format data or Factory reset
9. Tap On Apply Update > Apply From Sideload 
>adb -d sideload GenesisOS-Utopia-Official*.zip

10. Reboot Done.

**P.S: * Name varies from build to build**