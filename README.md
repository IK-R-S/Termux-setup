Run these following commands to `setup.sh`:

```
chmod +x setup.sh; ./setup.sh
```
## Essential utilities (setup.sh)
```
clear
termux-change-repo
pkg install termux-am
termux-setup-storage
apt update
apt upgrade -y
apt install git python3 nodejs neofetch
pkg install rust
apt-get install binutils
clear
neofetch
echo "Setup finished, run bash"
echo " "
```

## Personalization
### Extra Keys (virtual keyboard)
```
mkdir ~/.termux; nano ~/.termux/termux.properties
```
### Startup message
```
nano /data/data/com.termux/files/usr/etc/motd
```
