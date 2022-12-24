# 云托管 弹性服务实例 应用汇总


## sockd：socks5 proxy

这个是一个socks5的代理端，通过在云托管的弹性服务实例上启动，可以获得一个socks5的代理服务端，可以适配海外游戏代理、电商店铺管理代理。具体使用说明可见文件夹内 readme 说明。

## ssr：shadowsocks-r proxy

这个是一个ssr的代理端，通过在云托管的弹性服务实例上启动，可以获得一个ssr的代理服务端，可以适配海外游戏代理、电商店铺管理代理。具体使用说明可见文件夹内 readme 说明。


## sockd_ssr：socks5 + shadowsocks-r proxy

这个是一个socks5+ssr的多合一代理端，通过在云托管的弹性服务实例上启动，可以获得一个多合一的代理服务端，可以适配海外游戏代理、电商店铺管理代理。具体使用说明可见文件夹内 readme 说明。



# 服务器容器化运行

docker run -d --network=host 2398872109/sockd_ssr

如果需要修改用户名密码，使用  -e xxx=xxx 方式修改；

具体各参数可见服务详细说明
