# TV-OS-LINUX
an alternative to unofficial android tv os for pc

it is based on Arch Linux with kodi with IPTV (Samsung TV Plus)

to connect your wifi follow this:
```bash
# exit from kodi first.
rfkill unblock all
iwctl
device list
station (yourdevice) connect (yourwifi)
Passphrase: your password
exit
kodi
```
