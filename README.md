# container start
docker-compose up -d

# container login
docker-compose exec web bash

## package install
(in container)
composer install

# url
http://localhost:8080/index.php

# docker image info
https://hub.docker.com/r/pointsandlines/php8-dev-starter/tags