FROM ubuntu:latest
RUN apt update
RUN apt install apache2 -y
CMD ["apache2ctl", "-D", "FOREGROUND"]
COPY index.html /var/www/html/ 
