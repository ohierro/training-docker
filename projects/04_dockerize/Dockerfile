FROM ubuntu:latest
MAINTAINER Óliver Hierro (ohierro@hiberus.com)

RUN apt-get update
RUN apt-get install -y nginx

EXPOSE 80

CMD service nginx start && tail -f /var/log/nginx/access.log
#ENTRYPOINT service nginx start && tail -f /var/log/nginx/access.log

COPY index.html /var/www/html

#ENTRYPOINT ["tail", "-f", "/var/log/nginx/access.log"]
