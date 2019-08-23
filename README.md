请根据需要自行选择

#github地址：
https://github.com/flyfeng2002/FYQ-Hackintosh

#码云地址：
https://gitee.com/flyfeng2002/FYQ-Hackintosh


# 笔记本配置  
电脑型号 DELL-G7-7588  
操作系统 macOS Mojave 10.14.5  
处理器  Intel Core i5-8400 @ 2.81GHz 六核  
内存 24GB 2667 MHz DDR4  
硬盘  WD SSD 1TGB PCIE NVME  
显卡 Intel UHD Graphics 630 (platform-id:0x3e9b0000)  
网卡 Intel AC9560更换为博通1820A  
声卡 ALC256(layout-id:56)  
SMBIOS MacBookPro15,1 (15-inch, 2018  




# DVMT 及 CFG修改参数：
1. setup_var 0x5BD 0x1
2. setup_var 0x8D2 0x2
3. setup_var 0x8D3 0x3

# CLOVER:

## 正常工作的功能

1. CPU 睿频变频正常
2. 核显 UHD630 成功驱动 显存设置为2048MB 硬件加速
3. USB3.0 正常 (USBPorts)
4. 声卡 DSDT 完美内建 layout-id 为 56
5. 电池正常
6. 亮度可调节
7. 亮度可保存
8. 睡眠唤醒正常
9. 有线网卡正常
10. 更换无线网卡为博通1820A，蓝牙、WIFI均正常
11. 雷电3接口可以视频输出，可以热插拔存储设备 
## 存在的问题

1. HDMI以及音频无法正常工作，无输出；
 


# OPENCORE:

## 正常工作的功能
1. CPU 睿频变频正常
2. 核显 UHD630 成功驱动 硬件加速
3. USB3.0 正常 (USBPorts)
4. 声卡 DSDT 完美内建 layout-id 为 56
5. 电池正常
6. 亮度可调节
7. 亮度可保存
8. 有线网卡正常
9. 睡眠唤醒正常
10. 更换无线网卡为博通1820A，蓝牙、WIFI均正常
11. 雷电3接口可以视频输出，可以热插拔存储设备

## 存在的问题

1. HDMI以及音频无法正常工作，无输出； 




参考：
https://github.com/Juan-VC/macOS-Mojave-on-Dell-G7-7588