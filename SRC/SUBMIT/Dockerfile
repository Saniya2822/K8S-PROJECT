FROM centos:latest
RUN sed -i 's/mirrorlist/#mirrorlist/g' /etc/yum.repos.d/CentOS-*
RUN sed -i 's|#baseurl=http://mirror.centos.org|baseurl=http://vault.centos.org|g' /etc/yum.repos.d/CentOS-*
#RUN yum update
RUN yum install httpd -y
CMD ["service", "httpd", "start"]
ENTRYPOINT echo "THIS IS SUBMIT POD" >/var/www/html/index.html
EXPOSE 8082
