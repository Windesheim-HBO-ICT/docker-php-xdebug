# Docker Xampp XDebug

## Installatie
- Clone de repository.
- Controleer of Docker Desktop is geïnstalleerd

## Uitvoeren

`docker-compose up -d --build php-fpm --build webserver --build db --build phpmyadmin`

## Applicaties

**PHP**
Plaats source code in de map `./src`. Bereikbaar in de browser op adres `http://localhost:8080`.

**PhpMyAdmin**
Bereikbaar in de browser op adres `http://localhost:8081`.

Inloggegevens:
http://localhost:8889
admin 
test

## Bronnen

**PHP and NGINX**  
https://marc.it/dockerize-application-with-nginx-and-php8/

**XDebug**  
https://matthewsetter.com/setup-step-debugging-php-xdebug3-docker/

**PhpMyAdmin**
https://github.com/phpmyadmin/docker
