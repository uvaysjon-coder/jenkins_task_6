FROM ubuntu:20.04
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get -y update
RUN apt-get -y install apache2

RUN echo "Hello Docker!' > /var/www/html/index.html
CMD ["/usr/sbin/apache2ctl", "-D" "FOREGROUND"]
EXPOSE 80