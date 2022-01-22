# public hub
FROM python:3.8

# Копируем файлы с хоста в =>образ=>контейнер
# При изменении файлов на хосте, в контейнере файлы не изменятся
COPY /stocks_products /stocks_products
# указываем рабочую директорию для последующих команд CMD
WORKDIR /stocks_products
# Устанавливаем библиотеки для проекта
RUN pip install --upgrade pip
RUN pip install -r /requirements.txt
