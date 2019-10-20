Dell Inspiron 5548 (4528S) for macOS Mojave  
====
这是我使用的Dell Inspiron 5548(4528S)的CLOVER引导文件，其他机型请自测  

电脑配置  
----
规格	详细信息  
电脑型号	戴尔 Inspiron 5548 笔记本电脑  
操作系统	macOS Mojave 10.14.6(18G87)  
处理器	英特尔 Core i5-5200U @ 2.70GHz 双核  
内存	8 GB  
硬盘	SanDisk SDSSDA240G (240 GB, SATA-III)  
显卡	Intel HD Graphics 5500  
显示器	BOEhydis NV156FHM-N61 15.6" LCD (FHD)(更换高分屏)  
声卡	ALC255  
网卡	英特尔3160已更换为Dell Wireless 1820A  
安装镜像  
----
[【黑果小兵】macOS Mojave 10.14.6 18G87 正式版 with Clover 5050原版镜像[双EFI双平台终极版]]  
(https://blog.daliansky.net/categories/%E4%B8%8B%E8%BD%BD/%E9%95%9C%E5%83%8F/)  

安装时请使用镜像自带Clover，安装完成后替换此EFI  
----
详情  
----
1、hotpatch补丁实现显卡驱动  
2、Cpufriend和CPUFriendDataProvider实现CPU变频  
3、DSDT补丁实现电量显示  
4、hotpatch补丁实现加载XCPM原始电源管理  
5、有线网卡可用，自带英特尔3160无线网卡更换为DW1820A后无线和蓝牙可用  
6、hotpatch补丁实现亮度调节，笔记本Fn快捷键可用  
7、声卡为ALC255，使用 AppleALC 仿冒，注入layout-id:11，麦克风未测试  
已知问题  
----
睡眠后不能唤醒
