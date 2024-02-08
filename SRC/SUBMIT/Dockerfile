FROM centos:latest
RUN sudo yum update
RUN sudo yum install httpd -y
CMD ["service", "httpd", "start"]
ENTRYPOINT echo "THIS IS SUBMIT POD" >/var/www/html/index.html
EXPOSE 8082
