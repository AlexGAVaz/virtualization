# Используем официальный образ Nginx
FROM nginx:latest

# Копируем кастомную индекс-страницу в образ
COPY index.html /usr/share/nginx/html/index.html

# Помечаем порт, который используется приложением
EXPOSE 80

# Команда, выполняемая при запуске контейнера
CMD ["nginx", "-g", "daemon off;"]

