合众恒越开发板部署dm collection流程
一：烧写固件：
1：   按住recovery 键上电，通过lsubs命令查看是否有nivada设备。
2：烧写命令：
     sudo ./flash.sh  -r p3449-0000+p3668-0001-qspi-emmc mmcblk0p1
       sudo ./flash.sh p3449-0000+p3668-0001-qspi-emmc mmcblk0p1
二：参考合众恒越文档对SD卡分区并将文件系统安装到 TF 卡。
三：采用nv SDK Manage 烧写jetson sdk componet 
（时间比较长等待）
四：
