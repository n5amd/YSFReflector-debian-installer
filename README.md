# YSFReflector-debian-installer
This is a simple script to install YSFReflector. This script essentially runs through the official steps found at: https://register.ysfreflector.de/installation for your convenience. All you need to provide before hand is have a Debian 9.x server ready and updated. 



### To install on Debian 9.x:
```sh
git clone https://github.com/n5amd/YSFReflector-debian-installer
cd YSFReflector-debian-installer
./YSFReflector-debian-installer
```

### To interact with ysfreflector after installation:
```sh
systemctl start|stop|status|restart ysfreflector
```
 - Installs to /ysfreflector
 - Logs are in /var/log/YSFReflector

**For more information, please visit:**

https://sadigitalradio.com/

