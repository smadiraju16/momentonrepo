FROM jwilder/nginx-proxy:latest

ADD ./conf/nginx.conf /etc/nginx/nginx.conf

VOLUME ["/var/run/docker.sock"]

EXPOSE 80 8080

