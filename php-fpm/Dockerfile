FROM php:5.6-fpm

RUN usermod -u 1000 www-data

RUN docker-php-ext-install mysqli

COPY ./application/index.php /var/www/html/index.php