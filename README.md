# Installer VPS
# For Debian Update
```
apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot
```
# For Ubuntu Update
```
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub && reboot
```

# Command Install
```
apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/VPN-EXECUTIVE/NEWSC/main/setup.sh && chmod +x setup.sh && ./setup.sh
```
# Install SSH-UDP
```
wget "https://raw.githubusercontent.com/VPN-EXECUTIVE/UDP-TUNNEL/main/udp-tunnel.sh" -O install-udp && chmod +x install-udp && ./install-udp
```
# Done
