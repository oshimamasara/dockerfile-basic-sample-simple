FROM ubuntu:18.10

LABEL version="1.0"
LABEL description="Dockerfileのテスト、git clone"

RUN apt-get update
RUN apt-get install -y apache2
RUN apt-get install -y git

RUN cd /var/www/html && git clone https://github.com/dionyziz/canvas-tetris.git

CMD ["apachectl", "-D", "FOREGROUND"]
