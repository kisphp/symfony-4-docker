FROM debian:jessie

RUN apt-get update && apt-get install -y nginx

RUN rm -rf /etc/nginx/sites-enabled/*

COPY ./vhosts/s4.conf /etc/nginx/sites-enabled/s4.conf

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]
