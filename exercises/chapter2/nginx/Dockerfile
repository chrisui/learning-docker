FROM nuagebec/ubuntu
MAINTAINER chrisui

RUN apt-get update
RUN apt-get install -y Nginx

COPY index.html /usr/share/nginx/html/index.html
COPY nginx.conf /etc/nginx/nginx.conf

CMD /etc/init.d/nginx start
