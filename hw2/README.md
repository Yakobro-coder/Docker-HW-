1. Запускаем сборку контейнеров по Dockerfile прописанных в docker-compose.yml и запускаем compose

`docker-compose up -d --build`

2. Делаем миграцию базы данных

`docker exec stocks_products_python_django_1 python manage.py migrate`

3. Собирем статику

`docker exec stocks_products_python_django_1 python manage.py collectstatic --no-input --clear`

------
