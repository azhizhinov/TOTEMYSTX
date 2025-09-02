# TOTEMYSTX
TOTEMYSTX is a 38-40 keys column-staggered split keyboard. It meant to be used with a Seed Studio XIAO RP2040 or nRF52840.
TOTEMYSTX is a replica of the famous TOTEM by GEIGEIGEIST for MX spacing (19.05x19.05mm) switches like Cherry MX.

**Warning. I don't have printed PCBs on hands, so can't check or debug. It should work in theory. Use this files on youre own risk.**

https://github.com/GEIGEIGEIST/TOTEM

TOTEMYSTX with 38 keys shares the same firmware as of the original TOTEM.
![image](./Pictures/20250812.AZHIZHINOV.TOTEMYSTX.00.jpg)
![image](./Pictures/20250812.AZHIZHINOV.TOTEMYSTX.01.jpg)

There are 3 mods for the TOTEMYSTX use cases.

The jumper is open. 38 keys as usual, but the right thumb key not in use, has no connection to the MCU.

![image](./Pictures/20250902.AZHIZHINOV.TOTEMYSTX.00.png)

If you'll cut out the outer thumb key, you have to solder the jumper in "TOTEMX" mode. It's will be classical TOTEM/TOTEMX.

![image](./Pictures/20250902.AZHIZHINOV.TOTEMYSTX.01.png)

To use all 40 keys, you have to solder the jumper in "TOTEMYSTX" mode and change a keymap and recompile then.

![image](./Pictures/20250902.AZHIZHINOV.TOTEMYSTX.02.png)

TOTEMX with 38 keys shares the same firmware as of the original TOTEM.
![image](./Pictures/20250812.AZHIZHINOV.TOTEMX.00.jpg)
![image](./Pictures/20250812.AZHIZHINOV.TOTEMX.01.jpg)

Cases's models are designed to use M2 screws. For the TOTEMYSTX case use M2\*10mm -8pcs and M2\*8mm -2pcs and M2\*10mm -8pcs for the TOTEMX case.
![image](./Pictures/20250814.SCREW.M2.00.jpg)
The cases and PCBs are not compatible with the previous version. https://github.com/azhizhinov/TOTEMX
