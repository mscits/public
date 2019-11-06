## UEFI mode require 64 bit OS

- CMD setup mOS 18.04 X64 LTS with VPN mOS 02
```
apt install git -y && \
git clone https://github.com/mscits/mOS-18.04-X64-LTS-VPNmOS02.git /tmp/mOS-18.04-X64-LTS-VPNmOS02/ && \
chmod +x /tmp/mOS-18.04-X64-LTS-VPNmOS02/setup.sh && \
sh /tmp/mOS-18.04-X64-LTS-VPNmOS02/setup.sh
```
- CMD setup mOS 18.04 X64 LTS
```
apt install git -y && \
git clone https://github.com/mscits/mOS-18.04-X64-LTS.git /tmp/mOS-18.04-X64-LTS/ && \
chmod +x /tmp/mOS-18.04-X64-LTS/setup.sh && \
sh /tmp/mOS-18.04-X64-LTS/setup.sh
```
- CMD setup mOS 18.04 X86 LTS
```
apt install git -y && \
git clone https://github.com/mscits/mOS-18.04-X86-LTS.git /tmp/mOS-18.04-X86-LTS/ && \
chmod +x /tmp/mOS-18.04-X86-LTS/setup.sh && \
sh /tmp/mOS-18.04-X86-LTS/setup.sh
```
- CMD setup mOS 19.04 X64
```
apt install git -y && \
git clone https://github.com/mscits/mOS-19.04-X64.git /tmp/mOS-19.04-X64/ && \
chmod +x /tmp/mOS-19.04-X64/setup.sh && \
sh /tmp/mOS-19.04-X64/setup.sh
```
- Setup VPN mOS 02
```
apt install git -y && \
git clone https://github.com/mscits/Setup-VPNmOS02.git /tmp/Setup-VPNmOS02/ && \
chmod +x /tmp/Setup-VPNmOS02/setup.sh && \
sh /tmp/Setup-VPNmOS02/setup.sh
```
- Setup AnyDesk X64
```
apt install git -y && \
git clone https://github.com/mscits/Setup-AnyDesk-X64.git /tmp/Setup-AnyDesk-X64/ && \
chmod +x /tmp/Setup-AnyDesk-X64/setup.sh && \
sh /tmp/Setup-AnyDesk-X64/setup.sh
```
- Enable Wifi auto start on mOS LocalDisk
  - Remove line @/usr/bin/nmcli radio wifi off
```
nano /home/mosuser/.config/lxsession/Lubuntu/autostart
```
- Setup Barrier X64 --> https://itsfoss.com/keyboard-mouse-sharing-between-computers/
```
sudo apt install snapd -y && \
sudo snap install barrier --edge && \
sudo reboot
```

- Enable Ubuntu 16.04 Repo
```
sudo nano /etc/apt/sources.list
```

```
###### Ubuntu Main Repos
deb http://mirror1.totbb.net/ubuntu/ xenial main restricted universe multiverse 

###### Ubuntu Update Repos
deb http://mirror1.totbb.net/ubuntu/ xenial-security main restricted universe multiverse 
deb http://mirror1.totbb.net/ubuntu/ xenial-updates main restricted universe multiverse 
deb http://mirror1.totbb.net/ubuntu/ xenial-backports main restricted universe multiverse 
```
```
sudo apt update -y
```
***
- Setup Ubuntu 18.04 K8S HAProxy
```
apt install git -y && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-K8S-HAProxy.git /tmp/Setup-Ubuntu18.04-K8S-HAProxy/ && \
chmod +x /tmp/Setup-Ubuntu18.04-K8S-HAProxy/setup.sh && \
sh /tmp/Setup-Ubuntu18.04-K8S-HAProxy/setup.sh
```