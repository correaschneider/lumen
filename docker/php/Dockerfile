FROM composer:latest

# lumen
RUN composer global require "laravel/lumen-installer"
ENV PATH="~/.composer/vendor/bin:${PATH}"

WORKDIR /var/www/html

CMD ["php", "-S", "0.0.0.0:9000", "-t", "public"]