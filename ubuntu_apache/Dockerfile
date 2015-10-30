FROM ubuntu

RUN apt-get update && apt-get install -y apache2

EXPOSE 80

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

ADD app/ /var/www/html
COPY app/ /var/www/html/app
