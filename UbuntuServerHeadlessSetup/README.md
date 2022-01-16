# How to enable wifi on Ubuntu Server 20.04 with Raspberry Pi 4

To perform this setup, you will need to connect your Raspberry Pi (with Ubuntu Server installed) to keyboard and display. Afterwards, you can use it headless, e.g. by connecting to it from laptop via ssh.

After logging into Ubuntu Server as a sudo user:

1. Update /etc/netplan/50-cloud-init.yaml file with wifi credentials (wifi hotspot name and password).
2. Apply changes (sudo netplan apply).
3. Reboot the system.

Tested on Ubuntu Server 20.04 and Raspberry Pi 4.
