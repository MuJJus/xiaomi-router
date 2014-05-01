Usage (Debian)
====
```
git clone https://github.com/MuJJus/xiaomi-router.git
apt-get install build-essential libelf1:i386
ln -s $HOME/xiaomi-router /opt/brcm-arm
export PATH=/opt/brcm-arm/bin:$PATH
export LD_LIBRARY_PATH=/opt/brcm-arm/lib

arm-linux-gcc
```
Tested on Debian 7.2
