FROM php:fpm-alpine

WORKDIR /var/www/html

# PHP Extentions
RUN docker-php-ext-install bcmath
RUN docker-php-ext-install pdo_mysql

EXPOSE 9000