# dockerTryApp
Base for Docker/Symfony/Vue

## setup
docker-compose up -d --build    <br/>
<br/>docker-compose up --build
<br/>docker exec -it php bash
<br/>
<br/>composer create-project symfony/website-skeleton .
<br/>composer require encore
<br/>docker-compose run --rm node yarn install

# Building
docker-compose run --rm node yarn run watch
