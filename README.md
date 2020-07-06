# ASROCK-Z370M-Pro4-BigSur
Computer configuration:
CPU： Intel i5-9600K
Mainboard：ASROCK-Z370M-Pro4
RAM：C9BJZ 8Gx2 OC-4133MHZ
Video：Powercolor RX580 8G
SSD：860EVO 500G

Introduction to the first edition:
Used bat.bat OpenCORE 0.6.0 2020-6-28
It can support the new installation of MacOS 11.0 beta bigsur, and can normally boot bigsur to install images and recovery
Using the latest development version of the three piece Lilu Weg fakesmc
Customized USB port and cpu-ssdt
Custom graphics card SSDT uses the native drive system to identify 580x, which can turn off whatever green
Customize other SSDT DSDT
Please modify and replace the ACPI patches according to your actual configuration

Normal equipment:
CPU USB network card video card sleep nvme SATA

Known problems:
The following problems are caused by the failure to load the kext driver in the installation image and recovery
1. The PS2 interface keyboard cannot be used in bigsur system installation interface and bigsur recovery interface. Please use USB keyboard and mouse
2. Using pm981 (a) hard disk in bigsur system installation interface and bigsur recovery interface may cause the system to be jammed and not solved temporarily.
3. To be found

instructions:
Directly decompress the boot file to the ESP partition. Note: please modify the SMBIOS serial number and other information in the configuration file. Do not use the SMBIOS information in the configuration file to log in to appleid to avoid blocking!
