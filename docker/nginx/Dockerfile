FROM nginx

WORKDIR /var/www/html

COPY ./docker/nginx/default.conf /etc/nginx/conf.d

COPY . /var/www/html

CMD ["nginx", "-g", "daemon off;"]