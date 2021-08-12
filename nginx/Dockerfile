FROM nginx:alpine

COPY conf/default.conf nginx_base:/etc/nginx/conf.d/
COPY ssl /etc/nginx/
COPY html /usr/share/nginx/