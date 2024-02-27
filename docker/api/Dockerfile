ARG PHP_VERSION=8.0

FROM php:${PHP_VERSION}-fpm

RUN apt-get update && apt-get install -y \
    git \
    curl \
    zip \
    unzip

WORKDIR /var/www/phpdockertest/api