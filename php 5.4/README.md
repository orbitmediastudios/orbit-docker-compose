# Docker compose file #

### For development with php 5.4 and mysql 5.5 ###

* You can switch mysql version if need it or replace with mariadb image. 
* Set MYSQL_ vars in _docker-vh/db_env.env_ file
* Mysql data diectory map to ```./data/db```.
* Current directory mount to ```/var/www/html```. You can update document root in _docker-vh/site.conf_.
* Logs could be viewed in _docker-vh/logs_.