# Symfony-Docker

## RUN Docker images 

RUN docker-compose up -d

## Git configuration

git config --global user.email 'your_email'

git config --global user.name 'your_name'

## Locate in Docker Project

RUN docker ps

symfony new my-project-name --full

docker exec -ti 'php_container_idd' bash

## Database Configuration

locate in my-project-name

modif file .env && rename this line 

DATABASE_URL="postgresql://db_user:db_password@127.0.0.1:5432/db_name?serverVersion=13&charset=utf8"

with 

DATABASE_URL="mysql://root:root@mysql:3306/test?serverVersion=5.7"