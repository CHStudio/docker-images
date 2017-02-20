FROM php:7.0-alpine
RUN apk --update add \
        git \
        g++ \
        make \
        autoconf \
        zlib-dev \
    && docker-php-ext-install mysqli pdo_mysql zip \
    && curl -sS https://getcomposer.org/installer | php \
    && mv composer.phar /usr/local/bin/composer \
    && pecl install xdebug && docker-php-ext-enable xdebug \
    && apk del g++ autoconf make
