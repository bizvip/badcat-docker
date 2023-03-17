FROM php:8.2.3-cli-alpine3.17

LABEL maintainer="archer"

RUN apk update && apk add git

COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer

#RUN #docker-php-ext-install zip gd
#RUN docker-php-ext-configure gd --enable-gd-native-ttf --with-freetype-dir=/usr/include/freetype2 --with-png-dir=/usr/include --with-jpeg-dir=/usr/include
#RUN docker-php-ext-enable gd
#RUN pecl install igbinary && docker-php-ext-enable igbinary
#RUN pecl install redis && docker-php-ext-enable redis

