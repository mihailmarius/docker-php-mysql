FROM php:8.1.19-apache
# For stability you can try debian buster version
# php:8.1.19-apache-buster
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli 
RUN docker-php-ext-install pdo pdo_mysql && docker-php-ext-enable pdo_mysql
COPY ./configuration/php.ini /usr/local/etc/php/php.ini
