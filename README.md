# Xray-config
xray server config backup
```
sudo git clone https://github.com/xiaotong6666/xray-config/ && cd xray-config && sudo chmod 777 ./* && sudo ./xray
```
客户端配置
```
vless://这里填UUID@127.0.0.1:80/?type=ws&encryption=none&path=%2Fvless&security=tls#
```
在VLESS中，中文也可以作为UUID，比如``这里填UUID``对应的UUID为``2d08bf76-cb9d-5286-b5b8-b4d0
575f5d60``该仓库的服务端配置文件可以直接使用，客户端配置需要把127.0.0.1修改为实际ip
