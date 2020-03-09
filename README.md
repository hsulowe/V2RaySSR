# V2RaySSR
 介绍：适用CentOS7，一键安装wordpress+v2ray_ws_tls
 
 作者：atrandys
 
 修改：波仔
 
 Youtube：波仔分享
 
 博客：www.v2rayssr.com
 
 已集成破解主题：D85.1、DUX6.0、Git主题（推荐使用）
 
 acme.sh的SSL证书申请为多域名适配，请输入绑定并解析的顶级域名（例：XXX.COM），请不要加上 www
 


yum install -y wget && wget https://raw.githubusercontent.com/V2RaySSR/hsulowe/master/v2ray_ws_tls_wp.sh && chmod +x v2ray_ws_tls_wp.sh && ./v2ray_ws_tls_wp.sh


本一键安装脚本，仅仅支持 centos 系统，大家请注意

以下是波仔GITHUB的命令

yum install -y wget && wget https://raw.githubusercontent.com/V2RaySSR/V2RaySSR/master/v2ray_ws_tls_wp.sh && chmod +x v2ray_ws_tls_wp.sh && ./v2ray_ws_tls_wp.sh
V2RAY 配置信息在以下目录

/etc/v2ray/myconfig.json

强制更新 SSL 证书

acme.sh --cron -f
本脚本集成了 PHP7.0+SQL5.6+WordPress 最新版+V2ray+Ws+Tls+WordPress 常用破解主题
