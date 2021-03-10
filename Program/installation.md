# Install

### update
```
sudo apt update
```
### pip3
```
sudo apt install python3-pip
```
### MySQL client
```base
sudo apt install mysql-client-core-5.7
mysql -u admin -p --host mysql8.ch5a6wy7rx8w.us-east-1.rds.amazonaws.com
```
### Apache
```
sudo apt install apache2
cat /etc/apache2/apache2.conf
sudo nano /var/www/html/index.html
sudo apachectl restart
```

### PHP
```
sudo apt install php
nano /var/www/html/index.php
<?php phpinfo(); ?>
```
### NodeJS
```
sudo apt install nodejs
sudo apt install npm
```
