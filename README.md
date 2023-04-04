# LEMP-docker
Yet another one Dockerized LEMP stack 

The purpose of this to create learning local enviroments. This docker enviroment is not suitable for production due to presence of the composer

the LEMP stack are:

    L is for Linux;
    E is for Nginx;
    M is for MySQL;
    P is for PHP.

# website
    
can be accessed in

`localhost`

src/  # Publicly accessible files at localhost

# phpmyadmin

you can access phpMyAdmin page by

`http://localhost:8080/`

Username: root

Password: root

login can by changed from docker-compose.yml file

# Composer

examples:

install phpmailer library from packagist

`docker-compose run --rm -w /var/www/app composer composer require  phpmailer/phpmailer`

available composer commands 

`docker-compose run --rm -w /var/www/app composer composer`

