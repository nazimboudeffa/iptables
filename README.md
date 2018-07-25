Edit the file

$ vi /etc/init.d/firewall

Once it's edited make it executable

$ chmod +x /etc/init.d/firewall

Make it beeing executable everytime

$ update-rc.d firewall defaults
