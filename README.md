# script-installation

```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update -y && apt install sudo && sudo apt install -y wget && sudo apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/vpnlegasi/script-install-access/main/install.sh && chmod +x install.sh && ./install.sh
```
