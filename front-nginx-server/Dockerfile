FROM nginx:latest

RUN apt-get -y update \
    && mkdir -p /var/www/vhosts/live_stream \
    && chmod -R 777 /var
COPY nginx.conf /etc/nginx/nginx.conf
COPY index.html /usr/share/nginx/html/index.html 