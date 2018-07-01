使用方法：

1.将wuliclient目录下载到 openwrt sdk packages 目录。

[编辑wuliclient.c，修改SER_ADRE SER_PORT为学校对应的网关IP地址和端口等]

2.回到sdk顶层目录

3.make

4.编译成功后生成一个.ipk文件在 ./bin/[platform]/packages/base/ 中

5.复制ipk到你的路由器上并安装它。

6.运行 wuliclent [学号] 1234 [eth0]

例如： wuliclent 130105021035 1234 eth0
