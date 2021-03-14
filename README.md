Dell Inspiron 5548 (4528S) for macOS big sur 11.2.3
====
这是我使用的Dell Inspiron 5548(4528S)的OpenCore 0.6.7引导文件，其他机型请自测  

电脑配置  

规格	详细信息  
电脑型号	戴尔 Inspiron 5548 笔记本电脑  
操作系统	macOS big sur 11.2.3  
处理器	英特尔 Core i5-5200U @ 2.70GHz 双核  
内存	8 GB  
硬盘	SanDisk SDSSDA240G (240 GB, SATA-III)  
显卡	Intel HD Graphics 5500  
显示器	BOEhydis NV156FHM-N61 15.6" LCD (FHD)(更换高分屏)  
声卡	ALC255  
网卡	英特尔3160已更换为Dell Wireless 1820A  

高分屏需要开启csm

efi-broadcom为dw1820a驱动
efi-intel为Intel无线网卡驱动

Intel无线网卡驱动暂未自测，有任何问题请反馈
