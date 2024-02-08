FROM ubuntu:latest
RUN apt update
RUN apt install apache2 -y
CMD ["service", "apache2", "start"]
ENTRYPOINT echo "THIS IS DASHBOARD" >/var/www/html/index.html
EXPOSE 8080
