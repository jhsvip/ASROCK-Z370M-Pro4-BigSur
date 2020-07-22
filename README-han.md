# ASROCK-Z370M-Pro4-BigSur

电脑配置：
CPU： Intel i5-9600K
Mainboard：ASROCK-Z370M-Pro4
RAM：C9BJZ 8Gx2 4133MHZ
Video：Powercolor RX580 8G
SATA-SSD：860EVO 500G
NVME-SSD： WD-SN750

版本简介：
使用了bat.bat的开发版本opencore0.6.0
使用了最新自编译版本Lilu WhatEverGreen，FakeSMC
可以支持Macos 11.0 beta BigSur全新安装，可正常引导BigSur安装镜像及Recovery
定制USB端口及CPU-SSDT
定制显卡SSDT 使用原生驱动 系统识别为580X 可关闭WhateverGreen
定制其他SSDT DSDT 
其中的各项acpi补丁请根据自己实际配置进行修改、替换

功能正常设备：
CPU USB 网卡 显卡 声卡 休眠 NVME SATA

已知问题：
1.在BigSur系统安装界面及BigSur Recovery界面使用PM981（a）硬盘安装系统可能会造成系统卡死。
2.待发现...

使用说明：
直接将压缩包解压缩后把EFI文件夹压缩至ESP分区即可。注意：请务必修改配置文件中SMBIOS的序列号等信息，不要使用配置中的SMBIOS信息登陆AppleID以免封号！
