怎么说呢 本来是打算安装 不过发现脚本里面的 caddy包 404了 然后就自己换了一下源

## 简介

ServerStatus-Toyo是一个可以同时监控多台服务器的云探针程序，直接使用一键脚本安装即可，即简单又方便

ServerStatus-Toyo是ServerStatu(https://github.com/tenyue/ServerStatus)项目的优化/修改版

## 安装

执行下面的代码下载再运行管理脚本

> wget -N --no-check-certificate https://raw.githubusercontent.com/4iri/Sundry/main/ServerStatus-Toyo/status.sh chmod +x status.sh

## 演示

https://jk.sunpma.com/

## 目录位置

安装目录：/usr/local/ServerStatus

网页文件：/usr/local/ServerStatus/web

配置文件：/usr/local/ServerStatus/server/config.json

客户端查看日志：tail -f tmp/serverstatus_client.log

服务端查看日志：tail -f /tmp/serverstatus_server.log

Caddy配置文件：/usr/local/caddy/caddy

## 参考

https://github.com/tenyue/ServerStatus

https://github.com/ToyoDAdoubi/ServerStatus-Toyo

https://www.aptx.xin/serverstatus-hotaru.html

https://lexsion.com/index.php/archives/124

https://sunpma.com/773.html
