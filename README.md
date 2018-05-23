# DEMP Stack: Docker + Nginx + MySQL + PHP

### Start DEMP Stack

`docker-compose up`

### Install PHP extensions

`docker exec [container id or name] docker-php-ext-install [extension] [extension]`

For example, installing PDO MySQL

`docker exec demp_php_1 docker-php-ext-install pdo pdo_mysql`