OpenWrt 是一个针对嵌入式设备的、高度可自定义化的、开源的Linux操作系统

此用于无线路由器的OpenWrt固件，源码库基于https://github.com/coolsnowwolf/lede

该固件适用AX6/AX3600，仅供有足够动手能力的个人使用，不保证稳定，不对因此固件而导致的任何问题负责。

含功能：

#SFE硬件加速

#NSS硬件加速（因上游lede源码库ECM重启BUG，移除ECM换用SFE，NSS其他组件保留『感谢Kaze大佬』）

#IPv6

#ttyd

#AdGuardhome

#酸酸乳plus（全组件）

#openclash小猫咪(与NSS冲突 二选一)

#全能推送

#上网时间控制

#动态DNS

#smartdns

#网络唤醒

#网易云解锁灰色歌曲

#KMS

#udpxy组播服务

#UPNP

#MWAN 3 分流助手

#IPSec VPN 服务器

#ZeroTier

#简单mesh

#QoS以及SQM QoS

#多线多拨

#负载均衡

#Turbo ACC 网络加速

#网络带宽监视器

本config集成大量常用插件，可自定义config配置文件

此项目为Actions，手动触发即可编译。
