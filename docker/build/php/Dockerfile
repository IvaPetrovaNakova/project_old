# docker/build/php/Dockerfile
# FROM httpd:2.4
FROM php:7.2-apache

# Copy Symfony files: COPY [FROM_MACHINE] [TO_CONTAINER]
COPY test.txt copied-test.txt

# COPY . ./htdocs -> remove this

COPY src/ /var/www/html/