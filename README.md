## INSTALL SCRIPT 
Masukkan perintah dibawah untuk menginstall Autoscript
```
rm -rf setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl &&  wget -q https://raw.githubusercontent.com/calayacalabag/script/main/setup.sh && chmod +x setup.sh && ./setup.sh
```
