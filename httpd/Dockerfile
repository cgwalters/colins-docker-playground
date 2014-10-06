FROM centos
RUN yum -y upgrade && yum -y install httpd && yum clean all
EXPOSE 80
CMD ["/bin/sh", "-c", "mkdir /run/httpd && exec /usr/sbin/httpd -D FOREGROUND"]
