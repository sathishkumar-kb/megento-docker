FROM nginx:latest

COPY rootfs /

VOLUME /var/www

RUN chown -R www-data:www-data /var/www
RUN chmod 755 /var/www

EXPOSE 80
