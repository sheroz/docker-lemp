FROM php:7-fpm
COPY ./php.ini /usr/local/etc/php/
COPY ./php.ini /usr/local/etc/php/conf.d/
RUN docker-php-ext-install mysqli pdo pdo_mysql