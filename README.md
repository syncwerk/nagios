# nagios
Various nagios plugins I've written over the years

[check_puppet.sh](https://github.com/sammcj/nagios/blob/master/check_puppet.sh) - Alerts if the Puppet agent not running, or is disabled.

![screen shot 2015-01-13 at 15 51 55](https://cloud.githubusercontent.com/assets/862951/5716193/31d87e46-9b3c-11e4-8e25-241358980cb3.png)

[check_pvgrub.sh](https://github.com/sammcj/nagios/blob/master/check_pvgrub.sh) - Check if any physical drive is NOT present in /boot/grub/device.map

[check_hvm.sh](https://github.com/sammcj/nagios/blob/master/check_hvm.sh) - Check if kernel version is 3.1X and alerts if HVM is not set

[check_sockets.sh](https://github.com/sammcj/nagios/blob/master/check_sockets.sh) - Check the number of sockets an application (Docker by default) is using and warn / alert if over a threshold
