FROM ubuntu:12.04
MAINTAINER Apasoft Formacion "apasoft.formacion@gmail.com"
RUN apt-get update
RUN apt-get install -y nginx
RUN echo 'Reto numero 2' > /usr/share/nginx/www/index.html
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
EXPOSE 80/tcp
EXPOSE 443/tcp