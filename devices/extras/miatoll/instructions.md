### Notes  
- Use Latest Regional FW
- Clean Flash Mandatory
- Use Genesis Recovery

### Prerequisite
- Recovery
- ROM

### How To Flash
1. Reboot To Fastboot by pressing 
>Vol Down + Power Button

2. Now Open CMD or Terminal in Your PC and connect your phone via USB
3. Now type 
>fastboot flash recovery recovery*.img

4. After Flashing now Reboot into Recovery by typing
>fastboot reboot recovery

or by pressing
>Volume Up + Power Button

5. After booting into Recovery click on Factory Reset and then do Format data or Factory reset
6. Select Apply Update using Sideload
7. Install the ROM by typing
>adb sideload GenesisOS-Official*.zip

8. Now Reboot to System

**P.S: * Name varies from build to build** 