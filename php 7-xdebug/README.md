# Docker compose file

### For development with php 7.0 and mysql 5.7

* You can switch mysql version if need it or replace with mariadb image. 
* Set MYSQL_ vars in _docker-vh/db_env.env_ file
* Mysql data diectory map to ```./data/db```.
* Current directory mount to ```/var/www/html```. You can update document root in _docker-vh/site.conf_.
* Logs could be viewed in _docker-vh/logs_.
* ```XDEBUG_CONFIG: "remote_host=10.254.254.254"``` - or your local ip. This could change based on your location.
* OR set this on your machine: ```sudo ifconfig en0 alias 10.254.254.254 255.255.255.0``` - we'll have alias with same ip so no need to tweak compose file - always have ```10.254.254.254```
* Need more test on windows