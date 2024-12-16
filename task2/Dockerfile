# Указываем базовый образ
FROM node:16-alpine

# Устанавливаем рабочую директорию
WORKDIR /home/ilovedocker/app

# Копируем файл hello.sh в рабочую директорию
COPY hello.sh /home/ilovedocker/app/

# Задаём команду запуска
CMD ["sh", "hello.sh"]
