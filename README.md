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
apt install git python3 nodejs neofetch -y
pkg install rust -y
apt-get install binutils -y
rm -rf /data/data/com.termux/files/usr/etc/motd-playstore
clear
neofetch
echo "Setup finished, run bash"
echo " "
```
![image](https://github.com/IK-R-S/Termux-setup/assets/73291742/fada8a70-b63d-44fc-aeaa-442ae893f816)
Select all, and after use one of the mirros.

## Personalization
### Extra Keys (virtual keyboard)
Create a new folder and file with this command:
```
mkdir ~/.termux; nano ~/.termux/termux.properties
```

save with your extra keys:
```
extra-keys = [['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]
```
### Startup message
```
nano /data/data/com.termux/files/usr/etc/motd
```
