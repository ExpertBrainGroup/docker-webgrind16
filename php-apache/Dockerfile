FROM expertbraingroup/webgrind16
MAINTAINER manish namdeo

RUN rm -f /usr/local/etc/php/conf/000-php.ini
ADD ./conf/000-php.ini /usr/local/etc/php/conf

RUN rm -f /etc/php5/mods-available/xdebug.ini
ADD ./conf/xdebug.ini /etc/php5/mods-available

RUN service apache2 restart
