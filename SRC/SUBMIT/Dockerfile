FROM centos:latest
RUN yum update
RUN yum install httpd -y
CMD ["service", "httpd", "start"]
ENTRYPOINT echo "THIS IS SUBMIT POD" >/var/www/html/index.html
EXPOSE 8082
