<!--
 * @Descripttion: 
 * @version: 
 * @Author: 鹿角兔子
 * @Date: 2021-08-30 20:49:29
 * @LastEditors: 鹿角兔子
 * @LastEditTime: 2021-08-30 20:49:30
-->
# 请启用虚拟机平台 Windows 功能并确保在BIOS中启用虚拟化

> 请启用虚拟机平台 Windows 功能并确保在BIOS中启用虚拟化

wsl2与大部分安卓模拟器冲突，大部分安卓模拟器会自动关闭Hyper-v

>  bcdedit /set hypervisorlaunchtype off  
关闭Hyper-v

> bcdedit /set hypervisorlaunchtype auto  
重启后打开Hyper-v
----
如果Ubntu界面显示空白，则在power-shell中输入
> wsl  

来启动ubntu