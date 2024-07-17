# Wordpress docker

- cp .env.example .env => Change the value .env file if you want
- docker compose up
- local run on: http://localhost:8000
- phpmyadmin run on: HTTP://localhost:8080
# If you want to change the config php.ini file, you only update the value in custom-php.ini file and then 
- docker compose down & docker compose up -d
# Check config in file
- run: docker compose exec -it wordpress bash
- run: php --ini to check the config PHP   