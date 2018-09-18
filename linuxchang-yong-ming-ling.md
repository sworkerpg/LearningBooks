# linux的常用命令基础

> * uname -r 查看当前系统内核版本
> * ls 列出当前目录下的文件
> * pwd 打印出当前位置
> * cd 切换目录位置
> * . 代表当前目录
> * .. 代表上层目录

## 分区跟目录

Windows分区在盘符下面，而linux分区挂在文件下面。

### U盘的使用

1. 查看U盘是否接入
   * fdisk -l  
2. 建立挂载节点
   * cd /mnt        
   * mkdir usb
3. 挂载命令
   * mount /dev/sdb1 /mnt/usb
4. 卸载命令
   * umount /mnt/usb

## 命令

> * / 根目录
> * clear\(Ctl + l\) 刷屏
> * ls -a 显示所有文件（包括隐藏文件）
> * rm -rf \*  r：递归删除 f：强制删除  （慎用）
> * mkdir myDir 创建名为myDir的目录
> * touch myTxt 创建名为myTxt的文件
> * mv 移动拷贝，重命名
> * cp 直接拷贝，可做备份
> * cat 查看文件内容



