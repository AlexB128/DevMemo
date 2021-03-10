# Install

### update
```base
sudo apt update
```
### pip3
```base
sudo apt install python3-pip
```
### MySQL client
```base
sudo apt install mysql-client-core-5.7
mysql -u admin -p --host mysql8.ch5a6wy7rx8w.us-east-1.rds.amazonaws.com
```
### Apache
```base
sudo apt install apache2
cat /etc/apache2/apache2.conf
sudo nano /var/www/html/index.html
sudo apachectl restart
```

### PHP
```base
sudo apt install php
nano /var/www/html/index.php
<?php phpinfo(); ?>
```
### NodeJS
```base
sudo apt install nodejs
sudo apt install npm
```
