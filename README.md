## UEFI mode require 64 bit OS

- CMD setup mOS 18.04 X64 LTS
```
apt install git -y && \
rm -rf /tmp/mOS-18.04-X64-LTS/ && \
git clone https://github.com/mscits/mOS-18.04-X64-LTS.git /tmp/mOS-18.04-X64-LTS/ && \
chmod +x /tmp/mOS-18.04-X64-LTS/setup.sh && \
sh /tmp/mOS-18.04-X64-LTS/setup.sh
```
- CMD setup mOS 18.04 X64 LTS with TeamViewer
```
apt install git -y && \
rm -rf /tmp/mOS-18.04-X64-LTS-TeamViewer/ && \
git clone https://github.com/mscits/mOS-18.04-X64-LTS-TeamViewer.git /tmp/mOS-18.04-X64-LTS-TeamViewer/ && \
chmod +x /tmp/mOS-18.04-X64-LTS-TeamViewer/setup.sh && \
sh /tmp/mOS-18.04-X64-LTS-TeamViewer/setup.sh
```
- CMD setup mOS 18.04 X64 LTS with VPN mOS 02
```
apt install git -y && \
rm -rf /tmp/mOS-18.04-X64-LTS-VPNmOS02/ && \
git clone https://github.com/mscits/mOS-18.04-X64-LTS-VPNmOS02.git /tmp/mOS-18.04-X64-LTS-VPNmOS02/ && \
chmod +x /tmp/mOS-18.04-X64-LTS-VPNmOS02/setup.sh && \
sh /tmp/mOS-18.04-X64-LTS-VPNmOS02/setup.sh
```

- CMD setup mOS 18.04 X86 LTS
```
apt install git -y && \
rm -rf /tmp/mOS-18.04-X86-LTS/ && \
git clone https://github.com/mscits/mOS-18.04-X86-LTS.git /tmp/mOS-18.04-X86-LTS/ && \
chmod +x /tmp/mOS-18.04-X86-LTS/setup.sh && \
sh /tmp/mOS-18.04-X86-LTS/setup.sh
```
- CMD setup mOS 19.04 X64
```
apt install git -y && \
rm -rf /tmp/mOS-19.04-X64/ && \
git clone https://github.com/mscits/mOS-19.04-X64.git /tmp/mOS-19.04-X64/ && \
chmod +x /tmp/mOS-19.04-X64/setup.sh && \
sh /tmp/mOS-19.04-X64/setup.sh
```
## DirectAdmin
- Update DirectAdmin Configuration CentOS 7
```
yum install git -y && \
rm -rf /tmp/Update-DA-Configuration-CentOS7/ && \
git clone https://github.com/mscits/Update-DA-Configuration-CentOS7.git /tmp/Update-DA-Configuration-CentOS7/ && \
chmod +x /tmp/Update-DA-Configuration-CentOS7/setup.sh && \
sh /tmp/Update-DA-Configuration-CentOS7/setup.sh
```

## Other
- Update mOS
```
sudo apt update -y && sudo apt upgrade -y && sudo apt autoremove -y
```
- Setup Conky
```
apt install git -y && \
rm -rf /tmp/Setup-Conky/ && \
git clone https://github.com/mscits/Setup-Conky.git /tmp/Setup-Conky/ && \
chmod +x /tmp/Setup-Conky/setup.sh && \
sh /tmp/Setup-Conky/setup.sh
```
- Setup FortiClient Free Antivirus (Ubuntu 18.04 LTS)
```
wget -O - https://repo.fortinet.com/repo/ubuntu/DEB-GPG-KEY | sudo apt-key add - && \
echo "deb [arch=amd64] https://repo.fortinet.com/repo/ubuntu/ /bionic multiverse" >> /etc/apt/sources.list && \
sudo apt update -y && \
sudo apt install forticlient -y
```
- Config Default boot to Windows
```
sed -i '6s/GRUB_DEFAULT=0/GRUB_DEFAULT=2/' /etc/default/grub && \
update-grub && \
sed -i '131s/Ubuntu/mOS-18.04-X64-LTS/' /boot/grub/grub.cfg && \
sed -i '148s/Ubuntu/mOS-18.04-X64-LTS/' /boot/grub/grub.cfg
```
- Config Default boot to mOS
```
sed -i '6s/GRUB_DEFAULT=2/GRUB_DEFAULT=0/' /etc/default/grub && \
update-grub && \
sed -i '131s/Ubuntu/mOS-18.04-X64-LTS/' /boot/grub/grub.cfg && \
sed -i '148s/Ubuntu/mOS-18.04-X64-LTS/' /boot/grub/grub.cfg
```
- CMD Setup TeamViewer X64
```
apt install git -y && \
rm -rf /tmp/Setup-TeamViewer-X64/ && \
git clone https://github.com/mscits/Setup-TeamViewer-X64.git /tmp/Setup-TeamViewer-X64/ && \
chmod +x /tmp/Setup-TeamViewer-X64/setup.sh && \
sh /tmp/Setup-TeamViewer-X64/setup.sh
```
- CMD Setup VPN mOS 02
```
apt install git -y && \
rm -rf /tmp/Setup-VPNmOS02/ && \
git clone https://github.com/mscits/Setup-VPNmOS02.git /tmp/Setup-VPNmOS02/ && \
chmod +x /tmp/Setup-VPNmOS02/setup.sh && \
sh /tmp/Setup-VPNmOS02/setup.sh
```
- CMD Setup AnyDesk X64
```
apt install git -y && \
rm -rf  /tmp/Setup-AnyDesk-X64/ && \
git clone https://github.com/mscits/Setup-AnyDesk-X64.git /tmp/Setup-AnyDesk-X64/ && \
chmod +x /tmp/Setup-AnyDesk-X64/setup.sh && \
sh /tmp/Setup-AnyDesk-X64/setup.sh
```
- Enable Wifi auto start on mOS LocalDisk
  - Remove line @/usr/bin/nmcli radio wifi off
```
nano /home/mosuser/.config/lxsession/Lubuntu/autostart
```
- CMD Setup Barrier X64 --> https://itsfoss.com/keyboard-mouse-sharing-between-computers/
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
- Setup USB Over Network
```
sudo apt install git -y && \
sudo rm -rf /tmp/Setup-USB-Over-Network-X64/ && \
sudo git clone https://github.com/mscits/Setup-USB-Over-Network-X64.git /tmp/Setup-USB-Over-Network-X64/ && \
sudo chmod +x /tmp/Setup-USB-Over-Network-X64/setup.sh && \
sudo sh /tmp/Setup-USB-Over-Network-X64/setup.sh
```

## K8S Series
- Setup Ubuntu 18.04 K8S HAProxy(Recommend use pfSene+HAProxy)
```
apt install git -y && \
rm -rf /tmp/Setup-Ubuntu18.04-K8S-HAProxy/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-K8S-HAProxy.git /tmp/Setup-Ubuntu18.04-K8S-HAProxy/ && \
chmod +x /tmp/Setup-Ubuntu18.04-K8S-HAProxy/setup.sh && \
sh /tmp/Setup-Ubuntu18.04-K8S-HAProxy/setup.sh
```
- Setup Ubuntu 18.04 K8S Master Single Node
```
sudo apt install git -y && \
rm -rf /tmp/Setup-Ubuntu18.04-K8S-Master/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-K8S-Master.git /tmp/Setup-Ubuntu18.04-K8S-Master/ && \
chmod +x /tmp/Setup-Ubuntu18.04-K8S-Master/setup-single.sh && \
sh /tmp/Setup-Ubuntu18.04-K8S-Master/setup-single.sh
```
- Setup Ubuntu 18.04 K8S HA Master First Node
```
sudo apt install git -y && \
rm -rf /tmp/Setup-Ubuntu18.04-K8S-Master/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-K8S-Master.git /tmp/Setup-Ubuntu18.04-K8S-Master/ && \
chmod +x /tmp/Setup-Ubuntu18.04-K8S-Master/setup-ha-stacked-first.sh && \
sh /tmp/Setup-Ubuntu18.04-K8S-Master/setup-ha-stacked-first.sh
```
- Setup Ubuntu 18.04 K8S HA Master Additional Node
```
sudo apt install git -y && \
rm -rf /tmp/Setup-Ubuntu18.04-K8S-Master/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-K8S-Master.git /tmp/Setup-Ubuntu18.04-K8S-Master/ && \
chmod +x /tmp/Setup-Ubuntu18.04-K8S-Master/setup-ha-stacked-additional.sh && \
sh /tmp/Setup-Ubuntu18.04-K8S-Master/setup-ha-stacked-additional.sh
```
- Setup Ubuntu 18.04 K8S HA Master Additional Node(Automate)
```
sudo apt install git -y && \
rm -rf /tmp/Setup-Ubuntu18.04-K8S-Master/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-K8S-Master.git /tmp/Setup-Ubuntu18.04-K8S-Master/ && \
chmod +x /tmp/Setup-Ubuntu18.04-K8S-Master/setup-ha-stacked-additional-automate.sh && \
sh /tmp/Setup-Ubuntu18.04-K8S-Master/setup-ha-stacked-additional-automate.sh
```
- Setup Ubuntu 18.04 K8S Worker Node
```
sudo apt install git -y && \
rm -rf /tmp/Setup-Ubuntu18.04-K8S-Worker/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-K8S-Worker.git /tmp/Setup-Ubuntu18.04-K8S-Worker/ && \
chmod +x /tmp/Setup-Ubuntu18.04-K8S-Worker/setup.sh && \
sh /tmp/Setup-Ubuntu18.04-K8S-Worker/setup.sh
```
- Setup Ubuntu 18.04 K8S Worker Node(Automate)
```
sudo apt install git -y && \
rm -rf /tmp/Setup-Ubuntu18.04-K8S-Worker/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-K8S-Worker.git /tmp/Setup-Ubuntu18.04-K8S-Worker/ && \
chmod +x /tmp/Setup-Ubuntu18.04-K8S-Worker/setup-automate.sh && \
sh /tmp/Setup-Ubuntu18.04-K8S-Worker/setup-automate.sh
```