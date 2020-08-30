FROM sramananece/apache
ENTRYPOINT apache2 -d FOREGROUND
RUN rm /var/www/html/index.html
ADD . /var/www/html

