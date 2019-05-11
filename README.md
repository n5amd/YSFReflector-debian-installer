# YSFReflector-debian-installer
This is a simple script to install YSFReflector and the YSFReflector Dashboard. This script essentially runs through the official steps found at: https://register.ysfreflector.de/installation and https://github.com/dg9vh/YSFReflector-Dashboard for your convenience. All you need to provide before hand is have a Debian 9.x server ready and updated and a FQDN for the web dashboard. 



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
 
After the installation your dashboard will be available at the FQDN you provided during setup.

**For more information, please visit:**

https://n5amd.com/

