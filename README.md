## UEFI mode require 64 bit OS

- CMD setup mOS 18.04 X64 with VPN mOS 02
```
apt install git -y && \
git clone https://github.com/mscits/mOS-18.04-X64-VPNmOS02.git /tmp/mOS-18.04-X64-VPNmOS02/ && \
chmod +x /tmp/mOS-18.04-X64-VPNmOS02/setup.sh && \
sh /tmp/mOS-18.04-X64-VPNmOS02/setup.sh
```
- CMD setup mOS 18.04 X64
```
apt install git -y && \
git clone https://github.com/mscits/mOS-18.04-X64.git /tmp/mOS-18.04-X64/ && \
chmod +x /tmp/mOS-18.04-X64/setup.sh && \
sh /tmp/mOS-18.04-X64/setup.sh
```
- CMD setup mOS 18.04 X86
```
apt install git -y && \
git clone https://github.com/mscits/mOS-18.04-X86.git /tmp/mOS-18.04-X86/ && \
chmod +x /tmp/mOS-18.04-X86/setup.sh && \
sh /tmp/mOS-18.04-X86/setup.sh
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
apt install git -y && \
git clone https://github.com/mscits/Setup-Barrier-X64.git /tmp/Setup-Barrier-X64/ && \
chmod +x /tmp/Setup-Barrier-X64/setup.sh && \
sh /tmp/Setup-Barrier-X64/setup.sh
```
https://itsfoss.com/keyboard-mouse-sharing-between-computers/