# alpine-hysteria2
在alpine中安装hysteria2
注意amd64构架 arm64构架
方法 uname -m
# x86_64 = amd64
# aarch64 = arm64
# i686 = 386

## 一键食用amd64
```
wget -O hy2.sh https://raw.githubusercontent.com/Heroyessj/alpine-hysteria2/main/hy2-amd64.sh  && sh hy2.sh
```
## 一键食用arm64
```
wget -O hy2.sh https://raw.githubusercontent.com/Heroyessj/alpine-hysteria2/main/hy2-arm64.sh  && sh hy2.sh
```

重复执行，会覆盖密码。  

## 说明：  
配置文件：/etc/hysteria/config.yaml  
使用自签名证书，默认端口40443，安全tls，SNI为： bing.com  
随系统自启动  
看状态 service hysteria status  
重启 service hysteria restart  

## 测试环境：  alpine 3.19.1  

## hy2官方：  
https://github.com/apernet/hysteria  

## xx工具中配置实例：  
<div align=center> <img src="image.png" width = 50%/> </div>




