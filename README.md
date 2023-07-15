# 安全客户端
# 一键安装脚本
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/735840086/SecClient/main/seclient.sh)"
```

开启服务
```bash
systemctl start seclient
```

重启服务
```bash
systemctl restart seclient
```
停止服务
```bash
systemctl stop seclient
```
安装好程序以后先执行开启服务命令 systemctl start seclient 然后 访问IP网页进行配置端口为21112  http://ip:21112
(openwrt系统 systemctl命令无效，须要用安装脚本菜单启动程序)



矿机连接 stratum+tcp://本地客户端IP:端口  

例：stratum+tcp://192.168.1.254:19001


适用于矿场，破解宽带运营商的连接数限制，数据加密更安全

# 特别注意
如果hhminer服务端后台没有上传自定义证书，那么安全客户端在添加端口的时候，是必须要勾选略过服务器证书检测,

