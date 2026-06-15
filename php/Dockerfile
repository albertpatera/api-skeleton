FROM php:8.3-fpm-alpine

RUN apk add --no-cache icu-dev icu-data-full pkgconf \
    && docker-php-ext-install intl pdo_mysql