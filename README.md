# NUC8-MOJAVE

作者：**Genius-lbesT**

**黑苹果Genius**

#### 关于NUC8:

![](https://github.com/Lubibest/NUC8-MOJAVE/blob/master/jpg/nuc8i7-features-16x9.png.rendition.intel.web.1648.927.png)



# 正文

本文将指导你安装最新版本的**MAC OS MOJAVE 10.14.5**

EFI支持：**10.14-10.14.5**

支持安装的机器：

**NUC8i7BEH**-酷睿™i7-8559U

**NUC8i5BEH**-酷睿™i5-8259U

**NUC8i3BEH**-酷睿™i5-8109U

[下载本教程附件](https://github.com/Lubibest/NUC8-MOJAVE/archive/master.zip)

### 一、安装教程：

[How-to-install-a-Hackintosh](https://github.com/Lubibest/How-to-install-a-Hackintosh)

### 二、指南

1、使用**nuc8-install-mojave5**文件包中的**EFI文件**进行安装

2、安装完成后使用**nuc8-after-install-mojave5**文件包中的**EFI文件**替换硬盘的**EFI分区**中的文件



### 三、说明

1、BIOS版本：0064

2、BIOS设置：

- `Boot -> Boot Configuration, disable "Network Boot"`
- `Power -> Secondary Power Settings, "Wake on LAN from S4/S5", set to "Stay Off"`
- `Boot -> Secure Boot, disable "Secure Boot"`
- `Devices -> OnBoard Devices, disable "Bluetooth" (macOS is not compatible well with Intel Wi-Fi/Bluetooth)`

建议：

- `Boot -> Boot Priority -> Legacy Boot Priority, enable "Legacy Boot".`

3、EFI中特别添加了：

- RTC补丁-没有这个补丁BIOS.0064无法安装或无法启动
- BIOS.0051不需要RTC补丁，使用本文的EFI正常启动（可选：在四叶草中将RTC补丁删除）

4、已添加隐藏启动项：

显示启动项：四叶草界面按F3显示隐藏

- Recovery
- Preboot

5、机型设置为Macmini8,1(机型设置为iMac可能造成风扇狂转)



### 四、关注我得到mac os更新的EFI更新支持



### 五、已知问题

ALC235使用的是万能声卡

雷电3热拔插(未确定)

三码未注入，如果无法登陆商店请注入三码或使用四叶草生成三码



### 六、本教程EFI

由

**垃圾帮主**修改制作

**Genius lbesT**发布

作者：**Genius-lbesT**

qq群：724096369

![](https://github.com/Lubibest/Hackintosh/blob/master/JPG/QQ.png)

 **黑苹果Genius**
