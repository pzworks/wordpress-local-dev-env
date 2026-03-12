FROM wordpress:php8.5-apache

ARG PUID=1000
ARG PGID=1000

RUN usermod -u ${PUID} www-data && groupmod -g ${PGID} www-data

COPY uploads.ini /usr/local/etc/php/conf.d/uploads.ini