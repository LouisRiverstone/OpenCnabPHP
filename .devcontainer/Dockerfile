FROM php:7.4.33-zts-alpine3.16

COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer

CMD ["tail", "-f", "/dev/null"]