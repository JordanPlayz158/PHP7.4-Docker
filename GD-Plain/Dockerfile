FROM php:7.4-fpm

RUN apt-get update && apt-get -y install zlib1g-dev libpng-dev \
    && docker-php-ext-install -j$(nproc) gd