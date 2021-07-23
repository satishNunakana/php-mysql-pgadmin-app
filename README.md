
# php-mysql-phpadmin

Php application with crud operations.

stack used: php
database: mysql
open source administration tool for MySQL: phpMyAdmin

build a image : docker build . -t amakundu/moe-php-mysql-demo:1.0.0

Docker run command : docker run -d -it -p 30001:80 --name "moe-php-mysql-app" -v "$(pwd):/var/www/html" amakundu/moe-php-mysql-demo:1.1.0

docker compose command : docker-compose up -d --build

Folder structure as per my dockerfile and docker-compose : docker-example\moe-php-mysql-demo\www>

if you face a problem like faild to build the project use:  docker rm -f $(docker ps -a -q) to remove all containers and  docker rmi $(docker images -a -q) for images
