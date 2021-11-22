FROM nginx:latest

RUN mkdir /intra
RUN mkdir /wiki

COPY conf/nginx.conf /etc/nginx/conf.d/default.conf
COPY conf/intra.conf /etc/nginx/conf.d/intra.conf

EXPOSE 80 8080
