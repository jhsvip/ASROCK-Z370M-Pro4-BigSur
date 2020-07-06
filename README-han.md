# ASROCK-Z370M-Pro4-BigSur

电脑配置：
CPU： Intel i5-9600K
Mainboard：ASROCK-Z370M-Pro4
RAM：C9BJZ 8Gx2 OC-4133MHZ
Video：Powercolor RX580 8G
SSD：860EVO 500G

首发版本简介：
使用了bat.bat的开发版本opencore0.6.0 2020-6-28 
可以支持Macos 11.0 beta BigSur全新安装，可正常引导BigSur安装镜像及Recovery
使用最新开发版本三件套lilu weg fakesmc
定制USB端口及CPU-SSDT
定制显卡SSDT 使用原生驱动 系统识别为580X 可关闭WhateverGreen
定制其他SSDT DSDT 
其中的各项acpi补丁请根据自己实际配置进行修改、替换

功能正常：
CPU USB 网卡 显卡 声卡 休眠 NVME SATA

已知问题：
由于在安装镜像及Recovery中无法加载Kext驱动造成以下问题
1.在BigSur系统安装界面及BigSur Recovery界面无法使用PS2接口键盘，请使用USB键盘鼠标
2.在BigSur系统安装界面及BigSur Recovery界面使用PM981（a）硬盘可能会造成系统卡死，暂时无解。
3.待发现...
