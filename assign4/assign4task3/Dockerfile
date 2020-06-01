FROM centos
MAINTAINER mukesh.7755@gmail.com
RUN yum install httpd -y
COPY website /var/www/html/
EXPOSE 80
ENTRYPOINT httpd -DFOREGROUND
