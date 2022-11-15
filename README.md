# online_shop_django

В данном репозитории находится backend-часть проекта онлайн-магазина. Написано на python (django).

### .env.prod 
* **DJANGO_ALLOWED_HOSTS** = ip-адрес сервера, на котором размещен backend; 
* **CORS_ALLOWED_ORIGINS** = http://ip-адресс:порт сервера, на котором размещен frontend; 
* **CURRENT_HOST** = http://ip-адресс:порт сервера, на котором будет работать backend.

## Локальный запуск контейнера (http://localhost:8000)
```
sudo docker-compose -f docker-compose-dev.yml up -d --build
```

## Production-запуск контейнера (http://внешний_ип_сервера:1337)
```
sudo docker-compose -f docker-compose-prod.yml up -d --build
```

Frontend для данного приложения находится [тут](https://github.com/im-not-tequila/online_shop_vue).
