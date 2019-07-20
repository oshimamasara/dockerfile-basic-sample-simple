FROM ubuntu:18.10

LABEL version="1.0"
LABEL description="Dockerfileのテスト、ファイルのコピペ"

RUN apt-get update
RUN apt-get install -y apache2

COPY hello.html /var/www/html/

CMD ["apachectl", "-D", "FOREGROUND"]