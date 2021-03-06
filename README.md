## Ubuntu Series
- Change mirror Ubuntu 18.04 & 20.04
```
sudo sed -i 's/\/th.archive.ubuntu.com/\/mirror1.totbb.net/g' /etc/apt/sources.list
```
- Install Ubuntu 18.04
```
apt install git -y && \
rm -rf /tmp/Setup-Ubuntu18.04/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04.git /tmp/Setup-Ubuntu18.04/ && \
chmod +x /tmp/Setup-Ubuntu18.04/setup.sh && \
sh /tmp/Setup-Ubuntu18.04/setup.sh
```
- Install Ubuntu 18.04 Zimbra LDAP (First Server)
```
apt install git -y && \
rm -rf /opt/Setup-Ubuntu18.04-Zimbra-LDAP/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-Zimbra-LDAP.git /opt/Setup-Ubuntu18.04-Zimbra-LDAP/ && \
chmod +x /opt/Setup-Ubuntu18.04-Zimbra-LDAP/setup.sh && \
sh /opt/Setup-Ubuntu18.04-Zimbra-LDAP/setup.sh
```
- Install Ubuntu 18.04 Zimbra Additional
```
apt install git -y && \
rm -rf /opt/Setup-Ubuntu18.04-Zimbra-Additional/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-Zimbra-Additional.git /opt/Setup-Ubuntu18.04-Zimbra-Additional/ && \
chmod +x /opt/Setup-Ubuntu18.04-Zimbra-Additional/setup.sh && \
sh /opt/Setup-Ubuntu18.04-Zimbra-Additional/setup.sh
```
- Install Ubuntu 18.04 Zimbra AIO
```
apt install git -y && \
rm -rf /opt/Setup-Ubuntu18.04-Zimbra-AIO/ && \
git clone https://github.com/mscits/Setup-Ubuntu18.04-Zimbra-AIO.git /opt/Setup-Ubuntu18.04-Zimbra-AIO/ && \
chmod +x /opt/Setup-Ubuntu18.04-Zimbra-AIO/setup.sh && \
sh /opt/Setup-Ubuntu18.04-Zimbra-AIO/setup.sh
```
- Install Ubuntu 20.04 Zimbra AIO
```
apt install git -y && \
rm -rf /opt/Setup-Ubuntu20.04-Zimbra-AIO/ && \
git clone https://github.com/mscits/Setup-Ubuntu20.04-Zimbra-AIO.git /opt/Setup-Ubuntu20.04-Zimbra-AIO/ && \
chmod +x /opt/Setup-Ubuntu20.04-Zimbra-AIO/setup.sh && \
sh /opt/Setup-Ubuntu20.04-Zimbra-AIO/setup.sh
```
- Install Ubuntu 20.04
```
apt install git -y && \
rm -rf /tmp/Setup-Ubuntu20.04/ && \
git clone https://github.com/mscits/Setup-Ubuntu20.04.git /tmp/Setup-Ubuntu20.04/ && \
chmod +x /tmp/Setup-Ubuntu20.04/setup.sh && \
sh /tmp/Setup-Ubuntu20.04/setup.sh
```
- Install Docker & Static IP
```
apt install git -y && \
rm -rf /tmp/Setup-Ubuntu20.04-Docker/ && \
git clone https://github.com/mscits/Setup-Ubuntu20.04-Docker.git /tmp/Setup-Ubuntu20.04-Docker/ && \
chmod +x /tmp/Setup-Ubuntu20.04-Docker/setup.sh && \
sh /tmp/Setup-Ubuntu20.04-Docker/setup.sh
```
- Install Docker & Portainer Agent & Static IP
```
apt install git -y && \
rm -rf /tmp/Setup-Ubuntu20.04-Docker-PortainerAgent/ && \
git clone https://github.com/mscits/Setup-Ubuntu20.04-Docker-PortainerAgent.git /tmp/Setup-Ubuntu20.04-Docker-PortainerAgent/ && \
chmod +x /tmp/Setup-Ubuntu20.04-Docker-PortainerAgent/setup.sh && \
sh /tmp/Setup-Ubuntu20.04-Docker-PortainerAgent/setup.sh
```
- Install Portainer & Static IP
```
apt install git -y && \
rm -rf /tmp/Setup-Ubuntu20.04-Portainer/ && \
git clone https://github.com/mscits/Setup-Ubuntu20.04-Portainer.git /tmp/Setup-Ubuntu20.04-Portainer/ && \
chmod +x /tmp/Setup-Ubuntu20.04-Portainer/setup.sh && \
sh /tmp/Setup-Ubuntu20.04-Portainer/setup.sh
```
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
- CMD setup mOS 20.04 X64 LTS
```
apt update -y && \
apt install git -y && \
rm -rf /tmp/mOS-20.04-X64-LTS/ && \
git clone https://github.com/mscits/mOS-20.04-X64-LTS.git /tmp/mOS-20.04-X64-LTS/ && \
chmod +x /tmp/mOS-20.04-X64-LTS/setup.sh && \
sh /tmp/mOS-20.04-X64-LTS/setup.sh
```
---
## DirectAdmin
- Update DirectAdmin Configuration CentOS 7 LAB
```
yum install git -y && \
rm -rf /tmp/Update-DA-Configuration-CentOS7-LAB/ && \
git clone https://github.com/mscits/Update-DA-Configuration-CentOS7-LAB.git /tmp/Update-DA-Configuration-CentOS7-LAB/ && \
chmod +x /tmp/Update-DA-Configuration-CentOS7-LAB/setup.sh && \
sh /tmp/Update-DA-Configuration-CentOS7-LAB/setup.sh
```
- Update DirectAdmin Configuration CentOS 7 Production
```
yum install git -y && \
rm -rf /tmp/Update-DA-Configuration-CentOS7-Production/ && \
git clone https://github.com/mscits/Update-DA-Configuration-CentOS7-Production.git /tmp/Update-DA-Configuration-CentOS7-Production/ && \
chmod +x /tmp/Update-DA-Configuration-CentOS7-Production/setup.sh && \
sh /tmp/Update-DA-Configuration-CentOS7-Production/setup.sh
```
---
## mOS & Ubuntu
- Update mOS
```
sudo apt update -y && sudo apt upgrade -y && sudo apt autoremove -y
```
- Setup Conky (mOS 18.04 & Lubuntu 18.04)
```
apt install git -y && \
rm -rf /tmp/Setup-Conky-mOS18.04/ && \
git clone https://github.com/mscits/Setup-Conky-mOS18.04.git /tmp/Setup-Conky-mOS18.04/ && \
chmod +x /tmp/Setup-Conky-mOS18.04/setup.sh && \
sh /tmp/Setup-Conky-mOS18.04/setup.sh
```
- Setup Conky (mOS 20.04 & Ubuntu 20.04)
```
apt install git -y && \
rm -rf /tmp/Setup-Conky-mOS20.04/ && \
git clone https://github.com/mscits/Setup-Conky-mOS20.04.git /tmp/Setup-Conky-mOS20.04/ && \
chmod +x /tmp/Setup-Conky-mOS20.04/setup.sh && \
sh /tmp/Setup-Conky-mOS20.04/setup.sh
```
`/usr/bin/conky -d -p 120 -c /home/mosuser/.conky/TeejeeTech/ProcessPanel`
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
- CMD Setup TeamViewer15 X64
```
apt install git -y && \
rm -rf /tmp/Setup-TeamViewer15-X64/ && \
git clone https://github.com/mscits/Setup-TeamViewer15-X64.git /tmp/Setup-TeamViewer15-X64/ && \
chmod +x /tmp/Setup-TeamViewer15-X64/setup.sh && \
sh /tmp/Setup-TeamViewer15-X64/setup.sh
```
- CMD Setup TeamViewer14 X64
```
apt install git -y && \
rm -rf /tmp/Setup-TeamViewer14-X64/ && \
git clone https://github.com/mscits/Setup-TeamViewer14-X64.git /tmp/Setup-TeamViewer14-X64/ && \
chmod +x /tmp/Setup-TeamViewer14-X64/setup.sh && \
sh /tmp/Setup-TeamViewer14-X64/setup.sh
```
- CMD Setup VPN mOS 01 (mOS 18.04 & Lubuntu 18.04)
```
apt install git -y && \
rm -rf /tmp/Setup-VPNmOS01-mOS18.04/ && \
git clone https://github.com/mscits/Setup-VPNmOS01-mOS18.04.git /tmp/Setup-VPNmOS01-mOS18.04/ && \
chmod +x /tmp/Setup-VPNmOS01-mOS18.04/setup.sh && \
sh /tmp/Setup-VPNmOS01-mOS18.04/setup.sh
```
- CMD Setup VPN mOS 02 (mOS 18.04 & Lubuntu 18.04)
```
apt install git -y && \
rm -rf /tmp/Setup-VPNmOS02-mOS18.04/ && \
git clone https://github.com/mscits/Setup-VPNmOS02-mOS18.04.git /tmp/Setup-VPNmOS02-mOS18.04/ && \
chmod +x /tmp/Setup-VPNmOS02-mOS18.04/setup.sh && \
sh /tmp/Setup-VPNmOS02-mOS18.04/setup.sh
```
- CMD Setup VPN mOS 02 (mOS 20.04 & Ubuntu 20.04)
```
apt install git -y && \
rm -rf /tmp/Setup-VPNmOS02-mOS20.04/ && \
git clone https://github.com/mscits/Setup-VPNmOS02-mOS20.04.git /tmp/Setup-VPNmOS02-mOS20.04/ && \
chmod +x /tmp/Setup-VPNmOS02-mOS20.04/setup.sh && \
sh /tmp/Setup-VPNmOS02-mOS20.04/setup.sh
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
echo '@/snap/bin/barrier %U' >> /home/mosuser/.config/lxsession/Lubuntu/autostart && \
sudo reboot
```
- Setup USB Over Network X64 (mOS 18.04 & Lubuntu 18.04)
```
sudo apt install git -y && \
sudo rm -rf /tmp/Setup-USB-Over-Network-X64-mOS18.04/ && \
sudo git clone https://github.com/mscits/Setup-USB-Over-Network-X64-mOS18.04.git /tmp/Setup-USB-Over-Network-X64-mOS18.04/ && \
sudo chmod +x /tmp/Setup-USB-Over-Network-X64-mOS18.04/setup.sh && \
sudo sh /tmp/Setup-USB-Over-Network-X64-mOS18.04/setup.sh
```
- Setup USB Over Network X86 (mOS 18.04 & Lubuntu 18.04)
```
sudo apt install git -y && \
sudo rm -rf /tmp/Setup-USB-Over-Network-X86-mOS18.04/ && \
sudo git clone https://github.com/mscits/Setup-USB-Over-Network-X86-mOS18.04.git /tmp/Setup-USB-Over-Network-X86-mOS18.04/ && \
sudo chmod +x /tmp/Setup-USB-Over-Network-X86-mOS18.04/setup.sh && \
sudo sh /tmp/Setup-USB-Over-Network-X86-mOS18.04/setup.sh
```
- Setup USB Over Network X64 (mOS 20.04 & Ubuntu 20.04)
```
sudo apt install git -y && \
sudo rm -rf /tmp/Setup-USB-Over-Network-X64-mOS20.04/ && \
sudo git clone https://github.com/mscits/Setup-USB-Over-Network-X64-mOS20.04.git /tmp/Setup-USB-Over-Network-X64-mOS20.04/ && \
sudo chmod +x /tmp/Setup-USB-Over-Network-X64-mOS20.04/setup.sh && \
sudo sh /tmp/Setup-USB-Over-Network-X64-mOS20.04/setup.sh
```
- Setup CA(Root Cert) (mOS 20.04 & Ubuntu 20.04)
```
sudo apt install git -y && \
sudo rm -rf /tmp/Setup-CA-mOS20.04/ && \
sudo git clone https://github.com/mscits/Setup-CA-mOS20.04.git /tmp/Setup-CA-mOS20.04/ && \
sudo chmod +x /tmp/Setup-CA-mOS20.04/setup.sh && \
sudo sh /tmp/Setup-CA-mOS20.04/setup.sh
```
- Setup Citrix Workspace (mOS 20.04 & Ubuntu 20.04)
```
sudo apt install git -y && \
sudo rm -rf /tmp/Setup-Citrix-Workspace-X64-mOS20.04/ && \
sudo git clone https://github.com/mscits/Setup-Citrix-Workspace-X64-mOS20.04.git /tmp/Setup-Citrix-Workspace-X64-mOS20.04/ && \
sudo chmod +x /tmp/Setup-Citrix-Workspace-X64-mOS20.04/setup.sh && \
sudo sh /tmp/Setup-Citrix-Workspace-X64-mOS20.04/setup.sh
```
- Remmina & FreeRDP Nightly Update Channel
```
sudo add-apt-repository ppa:remmina-ppa-team/remmina-next-daily -y && \
sudo add-apt-repository ppa:remmina-ppa-team/freerdp-daily -y && \
sudo apt-get update -y && sudo apt upgrade remmina -y
```
- OpenVPN Client Fast Update Channel (Ubuntu 18.04 Only)
```
sudo wget -O - https://swupdate.openvpn.net/repos/repo-public.gpg | apt-key add - && \
sudo echo "deb http://build.openvpn.net/debian/openvpn/stable bionic main" >> /etc/apt/sources.list && \
sudo apt update -y && sudo apt upgrade openvpn -y
```
- Setup indicator-ip (mOS 20.04 & Ubuntu 20.04)
```
sudo apt-add-repository ppa:bovender/bovender -y && \
sudo apt update -y && \
sudo apt install indicator-ip -y
```
---
## K8S
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