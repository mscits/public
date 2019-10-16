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
- Setup Barrier X64
```
sudo apt install snapd -y && \
sudo snap install barrier --edge && \
sudo reboot
```
https://itsfoss.com/keyboard-mouse-sharing-between-computers/