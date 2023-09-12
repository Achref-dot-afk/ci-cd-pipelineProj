FROM debian:latest

RUN apt update && apt install -y apache2 git

RUN git clone https://github.com/Krishnamohan-Yerrabilli/static-site.git

RUN cp -r static-site/'Practise third attempt'/* /var/www/html/

CMD ["apache2ctl", "-D", "FOREGROUND"]

EXPOSE 80
