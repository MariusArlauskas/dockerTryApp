# dockerTryApp
Base for Docker/Symfony/Vue

## setup
docker-compose up -d --build
docker-compose up --build
docker exec -it php bash

composer create-project symfony/website-skeleton .
cd
composer require encore
docker-compose run --rm node yarn install

# Building
docker-compose run --rm node yarn run watch