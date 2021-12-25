1. Собираем образ по "Dockerfile" из текущей директории

`docker build -t python_django .`  
Имя образа - _python_django_

2. Запускаем контейнер с образа

`docker run --name django_prod -d -p 5001:8000 python_django`

Имя контейнера - _django_prod_

------
