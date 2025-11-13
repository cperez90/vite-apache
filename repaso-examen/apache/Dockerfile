FROM httpd:2.4
LABEL authors="riku"

RUN mkdir -p /var/www/vite

COPY apache/httpd.conf /usr/local/apache2/conf/httpd.conf
COPY apache/httpd-vhosts.conf /usr/local/apache2/conf/extra/httpd-vhosts.conf