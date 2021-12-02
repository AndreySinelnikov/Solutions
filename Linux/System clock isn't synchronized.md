### CONTEXT: 

Manjaro XFCE clock isn't synchronized after installation.

### SOLUTION: 

Run in terminal:

systemctl disable ntpd.service
systemctl stop ntpd.service
systemctl start systemd-timesyncd.service
systemctl enable systemd-timesyncd.service
