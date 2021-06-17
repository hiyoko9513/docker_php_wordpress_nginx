FROM wordpress:5-php7.4-fpm

# php.ini
COPY php.ini /usr/local/etc/php/conf.d

RUN pecl install xdebug \
  && docker-php-ext-enable xdebug
