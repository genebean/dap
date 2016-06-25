FROM centos/httpd-24-centos7
MAINTAINER  Gene Liverman <gene@technicalissues.us>

#RUN sed -i 's/^\(Listen.*$\)/#\1/' /opt/rh/httpd24/root/etc/httpd/conf/httpd.conf

COPY ./conf.modules.d/ /opt/rh/httpd24/root/etc/httpd/conf.modules.d/
COPY ./conf.d/ /opt/rh/httpd24/root/etc/httpd/conf.d/

#COPY ./public-html/ /opt/rh/httpd24/root/var/www/html/
#RUN mkdir -p /docroot/html
#COPY ./public-html/ /docroot/html

