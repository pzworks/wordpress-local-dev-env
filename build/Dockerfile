FROM wordpress:php8.4-apache

ARG PUID=1000
ARG PGID=1000

RUN usermod -u $PUID www-data && groupmod -g $PGID www-data
