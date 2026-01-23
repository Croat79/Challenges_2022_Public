FROM php:8.5.2-apache

RUN mv "$PHP_INI_DIR/php.ini-production" "$PHP_INI_DIR/php.ini"

COPY index.php /var/www/html/index.php
COPY flag /flag
