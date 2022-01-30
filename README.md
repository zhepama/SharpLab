# SharpLab

C# compiler playground.

## ubuntu 安装net6.0

```
wget https://packages.microsoft.com/config/ubuntu/21.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
dpkg -i packages-microsoft-prod.deb
rm packages-microsoft-prod.deb
apt-get update
apt-get install -y apt-transport-https 
apt-get update 
apt-get install -y dotnet-sdk-6.0
```

## 启动ss

```
sslocal -c /etc/shadowsocks.json -d start     
```
