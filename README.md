# DEMP Stack: Docker + Nginx + MySQL + PHP

### Start Sever

`docker-compose up`

### Install PHP Extensions

`docker exec [container id or name] docker-php-ext-install [extension] [extension]`

For example, installing PDO MySQL

`docker exec demp_php_1 docker-php-ext-install pdo pdo_mysql`