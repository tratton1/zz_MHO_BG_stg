FROM quay.io/centos7/httpd-24-centos7
LABEL org.opencontainers.image.authors="tommy.ratton2@hcahealthcare.com"
ADD index.html /var/www/html/
USER 1001
## RUN echo "ServerName localhost:6789" >> /etc/httpd/conf/httpd.conf
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80/tcp
