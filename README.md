# Docker php8.2 MySql version 8 phpmyadmin and version 3.8 for yml
This is an alternative for LAMP setups for backend web development. I hope wil be useful.

# Php
Default php 8.1 with PDO and mysqli activated.
The folder where you put the php scripts is in "php/www"
You can change php.ini parameters in "php/configuration/php.ini"

# Mysql 8.0
If you want to change root password, find and change in "docker-compose.yml" MYSQL_ROOT_PASSWORD and change toor with your password.
You will found in "db-server" and in "phpmyadmin"
You can create table for your application and insert data in mysql/dump and edit "default.sql" file

# phpMyAdmin
Connect with MySql credentials!

# Tested
This project was tested in Ubuntu 22 and Debian 11

# Troubles
Depending on your configuration it may take a while for the mysql server to start. To be able to connect to the database, after starting the server, you have to wait for the period.