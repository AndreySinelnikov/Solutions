### CONTEXT: 

Manjaro XFCE clock isn't synchronized after installation.

### SOLUTION: 

Turn on recommended systemd synchronization service.

_Run in terminal:_

systemctl disable ntpd.service

systemctl stop ntpd.service 

systemctl start systemd-timesyncd.service 

systemctl enable systemd-timesyncd.service
