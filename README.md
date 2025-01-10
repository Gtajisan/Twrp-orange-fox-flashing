# Twrp-orange-fox-flashing
thes command you flash twrp or orange fox without pc
### command installation one line 
```
pkg update && upgrade && pkg install git && pkg install vim && pkg install curl && pkg install wget
```
### clone these repo
```
git clone https://github.com/Gtajisan/Twrp-orange-fox-flashing && cd Twrp-orange-fox-flashing && ls
```
### Package Install
Run `setup.sh` to install required packages.
```
chmod +x setup.sh && ./setup.sh
```

1.check you're device 
Type fastboot devices and press Enter just to be sure your device is correctly recognized.
```
mi-fastboot devices
```
2. recovery flash command 1st.
```
mi-fastboot flash recovery recovery.img
```
3. if you open twrp
```
mi-fastboot boot recovery.img
```
4. Type fastboot reboot and press Enter to reboot your device after the flash is complete.
```
mi-fastboot reboot
```
