How to enable your wifi on Ubuntu Server 20.04 with RaspberryPi 4

To perform this setup, you will need to connect your RaspberryPi with Ubuntu Server installed to keyboard and display. Afterwards, you can use your Ubuntu Server headless, e.g. connecting to it from your laptop via ssh and operating remotely.

Basically, there are just three simple steps you need to perform after you log in to your server as a sudo user:

1. Update /etc/netplan/50-cloud-init.yaml file with your wifi credentials (wifi hotspot name and password).
2. Apply changes (sudo netplan apply).
3. Reboot the system.

Tested on Ubuntu Server 20.04 and RaspberryPi 4.
