FROM php:8.2-fpm-alpine

RUN docker-php-ext-install \
    pdo_mysql

WORKDIR /var/www/laravel

COPY --from=composer:latest /usr/bin/composer /usr/bin/composer

USER www-data

EXPOSE 9000
