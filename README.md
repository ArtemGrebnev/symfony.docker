Для запуска в режиме девелоп использовать команду
```textmate
 docker-compose -f docker-compose.yaml -f docker-compose.development.yaml up --build
``` 

Для запуска в режиме продакшн 
```textmate
 docker-compose up --build
``` 

Для входа на сайт по домен именю локально нужно в etc/hosts 
```textmate
 127.0.0.1   название сайта например: symfony.learn.docker.com
             и также указать название сайта в конфиге nginx
``` 