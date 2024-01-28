FROM php:8.1.0-fpm

RUN pecl install xdebug && docker-php-ext-enable xdebug

COPY ./_docker/app/php.ini /usr/local/etc/php/conf.d/php.ini

WORKDIR /var/www/application

