# NUC8-MOJAVE

作者：**Genius-lbesT** QQ2489050703

加入QQ群：724096369 **黑苹果Genius**

#### 关于NUC8:

![](https://github.com/Lubibest/NUC8-MOJAVE/blob/master/jpg/nuc8i7-features-16x9.png.rendition.intel.web.1648.927.png)



# 正文

本文将指导你安装最新版本的MAC OS MOJAVE 10.14.5



### 一、安装教程：

https://github.com/Lubibest/How-to-install-a-Hackintosh



### 二、指南

1、使用nuc8-install-mojave5文件包中的EFI文件进行安装

2、安装完成后使用nuc8-after-install-mojave5文件包中的EFI替换硬盘的EFI分区中的文件



### 三、说明

1、BIOS版本：0064

2、BIOS设置：

Then change:

- Boot -> Boot Configuration, disable "**Network Boot**"
- Power -> Secondary Power Settings, "**Wake on LAN from S4/S5**", set to "**Stay Off**"
- Boot -> Secure Boot, disable "**Secure Boot**"
- Devices -> OnBoard Devices, disable "**Bluetooth**" (macOS is not compatible well with Intel Wi-Fi/Bluetooth)

Suggested:

- Boot -> Boot Priority -> Legacy Boot Priority, enable "**Legacy Boot**".

3、EFI中特别添加了：

- RTC补丁-没有这个补丁BIOS.0064无法安装或无法启动

4、已添加隐藏启动项：

- Recovery
- Preboot



### 四、关注我得到mac os更新的EFI更新支持



### 五、已知问题

ALC235使用的是万能声卡

雷电3热拔插(未确定)



### 六、本教程EFI

由

-垃圾帮主-修改制作

-Genius lbesT-发布

作者：Genius-lbesT QQ2489050703

加入QQ群：724096369 黑苹果Genius
