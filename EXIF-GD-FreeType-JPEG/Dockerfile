FROM jordanplayz158/php7.4-gd:exif

RUN apt-get update && apt-get -y install \
        libfreetype6-dev \
        libjpeg62-turbo-dev \
        libpng-dev \
    && docker-php-ext-configure gd --with-freetype --with-jpeg \
    && docker-php-ext-install -j$(nproc) gd