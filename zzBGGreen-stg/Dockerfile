FROM quay.io/centos7/httpd-24-centos7
LABEL org.opencontainers.image.authors="tommy.ratton2@hcahealthcare.com"
COPY index.html /var/www/html/
## RUN echo "ServerName localhost:6790" >> /etc/httpd/conf/httpd.conf
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80/tcp
