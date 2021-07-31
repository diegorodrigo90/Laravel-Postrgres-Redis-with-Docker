FROM php:fpm-alpine

RUN set -ex \
  && apk --no-cache add \
    postgresql-dev

RUN docker-php-ext-install pdo pdo_pgsql

RUN mkdir -p /application
RUN chown -R www-data:www-data /application
WORKDIR /application



EXPOSE 9000
