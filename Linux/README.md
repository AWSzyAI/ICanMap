# Linux

1.查看Linux系统版本命令
```
lsb_release -a //系统版本、LinuxStandard Base
uname -a //内核信息
cat /proc/version //操作系统版本信息
cat /proc/cpuinfo //查看Linux cpu相关信息、型号、主频、内核
getconf LONG_BIT //查看当前系统位数
```
2.将uBuntu22.04安装至U盘中使用BIAS启动？
```
在需要安装 Ubuntu 的电脑上插上系统启动盘。开机后按 F2 进入 BIOS 修改磁盘启动顺序，把 U 盘插的那个 USB 口设置成第一顺序启动，保存并退出 BIOS。
```
3.[ ]ubuntu 不联网，ping any server may loss 100% packages？

