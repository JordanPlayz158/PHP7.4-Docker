FROM jordanplayz158/php7.4:exif

RUN apt-get update && apt-get -y install zlib1g-dev libpng-dev \
    && docker-php-ext-install -j$(nproc) gd