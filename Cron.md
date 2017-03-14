Run
```sh
sudo crontab -e
```
put this in the file
```sh
0 0,4,8,12,16,20 * * * /usr/bin/php -f /path/to/phpmixbill/system/cron.php
```
this will run every 4 hours, tho check if there any expired customer

Every system have different configuration for crontab