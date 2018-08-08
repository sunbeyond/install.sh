# install.sh

### shadowsocks

- 安装
```
wget -O install-shadowsocks.sh https://gitee.com/sunbeyond/install.sh/raw/master/install-shadowsocks.sh
chmod +x install-shadowsocks.sh && ./install-shadowsocks.sh
```
- github源：https://raw.githubusercontent.com/sunbeyond/install.sh/master/install-shadowsocks.sh
- 支持 centos 7
- centos6下需要先update，否则版本太低
```
yum -y update nss curl
```
- 遇到 shadowsocks 启动失败，缺少`libsodium`时，则
```
yum install epel-release
yum install libsodium
```
