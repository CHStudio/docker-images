FROM php:7.0-alpine
RUN apk --update add \
        git \
        unzip \
        g++ \
        make \
        autoconf \
        zlib-dev \
    && curl -sS https://getcomposer.org/installer | php \
    && mv composer.phar /usr/local/bin/composer \
    && docker-php-ext-install pdo_mysql zip \
    && pecl install xdebug && docker-php-ext-enable xdebug \
    && apk del g++ autoconf make