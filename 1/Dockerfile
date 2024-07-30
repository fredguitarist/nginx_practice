# Используем базовый образ nginx:1.22
FROM nginx:1.22

# Копируем конфигурационный файл nginx.conf в контейнер
COPY ./nginx/nginx.conf /etc/nginx/nginx.conf

# Копируем статические файлы в контейнер
COPY ./static-website/ /usr/share/nginx/html/

