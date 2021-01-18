# important_files

## compat-wireless-2010-06-26-p.tar.bz2
Use this file when you are trying to run aircrack-ng, airmon-ng, and iwconfig on your Kali Linux VM from a Macbook localhost.
### Problem this solves:
I'm running Kali Linux in VirtualBox on a macbook.
Trying to test wifi security tools like aircrack-ng, airmon-ng, and iwconfig but there is no wlan0 network (because of Macbook hardware)
### How to use:
- Download this file to your Kali Linux box and cd to its location
- `tar -xjvf compact-wireless-2010–06–26-p.tar.bz2`
- `cd compat-wireless-2010–06–26-p`
- `make load`
### Verify it's working correctly
- `ifconfig` # should show you wlan0 and wlan1
- `iwconfig` # should show you your wireless networks

