# php-stack
stack for portainer including php, apache, mariadb, phpmyadmin

php-apache dockerfile is just a pull from the php:apache image with the sql extension
these enviroment variables should be setted up
- MYSQL_ROOT_PASSWORD: MYSQL_ROOT_PASSWORD
- MYSQL_DATABASE: MYSQL_DATABASE
- MYSQL_USER: MYSQL_USER
- MYSQL_PASSWORD: MYSQL_PASSWORD

recommendation:
https://www.section.io/engineering-education/dockerized-php-apache-and-mysql-container-development-environment/
