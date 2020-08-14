FROM centos
MAINTAINER shahsamkit35@gmail.com
RUN dnf install httpd -y 
CMD /usr/sbin/httpd -DFOREGROUND
COPY index.html /var/www/html/index.html
