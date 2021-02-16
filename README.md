# Symfony-Docker

RUN docker-compose up -d

git config --global user.email 'your_email'

git config --global user.name 'your_name'

RUN docker ps

docker exec -ti 'php_container_idd' bash

symfony new my-project-name --full

enter to .env and rename this line 

DATABASE_URL="postgresql://db_user:db_password@127.0.0.1:5432/db_name?serverVersion=13&charset=utf8"

with 

DATABASE_URL="mysql://root:root@mysql:3306/test?serverVersion=5.7"