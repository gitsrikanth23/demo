FROM ubuntu

MAINTAINER srikanth<reachoutsrikanth@gmail.com>

RUN yum install httpd git -y

RUN git clone https://www.github.com/abhiramIT/html.git /var/www/html

CMD ["httpd","_DFOREGROUND"]

