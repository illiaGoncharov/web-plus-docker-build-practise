# Указываем базовый образ
FROM node:16-alpine

# Устанавливаем рабочую директорию
WORKDIR /home/ilovedocker/app

# Копируем package.json и package-lock.json в рабочую директорию
COPY packages/package.json packages/package-lock.json ./

# Устанавливаем зависимости
RUN npm install

# Копируем исходники проекта в рабочую директорию
COPY src/ .

# Указываем порт, который будет использоваться
EXPOSE 3032

# Задаём команду запуска
CMD ["node", "main.js"]
