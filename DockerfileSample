# Volumeセット

FROM ubuntu:18.10

LABEL version="1.0"
LABEL description="Dockerfileのテスト、Volumeの設定"

RUN apt-get update
RUN apt-get install -y apache2

VOLUME ["/var/www/html"]

CMD ["apachectl", "-D", "FOREGROUND"]
