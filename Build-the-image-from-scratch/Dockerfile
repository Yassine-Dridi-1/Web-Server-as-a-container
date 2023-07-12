FROM ubuntu:latest
ENV DEBIAN_FRONTEND=noninteractive 
RUN apt update ; \
    apt install -y apache2 ; \
    apt-get install -y php libapache2-mod-php ; \
    apt-get clean ; \
    rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* 
COPY . /var/www/html/
EXPOSE 80 
CMD ["apache2ctl", "-D", "FOREGROUND"]
