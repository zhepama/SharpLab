# SharpLab

C# compiler playground.

## 安装git2

```
yum install https://packages.endpointdev.com/rhel/7/os/x86_64/endpoint-repo.x86_64.rpm
yum install git -y
```

## ubuntu 安装net6.0

```bash
wget https://packages.microsoft.com/config/ubuntu/21.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
dpkg -i packages-microsoft-prod.deb
rm packages-microsoft-prod.deb
apt-get update
apt-get install -y apt-transport-https 
apt-get update 
apt-get install -y dotnet-sdk-6.0
```

## centeros 安装net6.0

```bash
sudo rpm -Uvh https://packages.microsoft.com/config/centos/7/packages-microsoft-prod.rpm
sudo yum install dotnet-sdk-6.0 
```

## centeros安装code server

```
curl -fOL https://github.com/cdr/code-server/releases/download/v$VERSION/code-server-$VERSION-amd64.rpm
sudo rpm -i code-server-$VERSION-amd64.rpm
sudo systemctl enable --now code-server@$USER
# Now visit http://127.0.0.1:8080. Your password is in ~/.config/code-server/config.yaml
sudo systemctl start code-server@$USER
sudo systemctl stop code-server@$USER
```
