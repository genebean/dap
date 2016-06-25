# dap -- Docker Apache PHP-FPM

This is a playground for me to learn about Docker
and how to build a multiserver setup where Apache
runs on one container and sends all PHP requests
to another container running php-fpm.

All work is being done using Docker >= 1.12

The frontend of this is built around a
CentOS 7 container running the httpd24
software collection ([centos/httpd-24-centos7][httpd24])

[httpd24]: https://hub.docker.com/r/centos/httpd-24-centos7/

