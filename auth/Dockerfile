# устанавливаем ПО
FROM node:13.12.0-alpine
#устанавливаем рабочую дерикторию
WORKDIR /usr/src/app
# копируем файлы в контейнер
COPY package*.json ./

RUN npm install
# копируем все  файлы в контейнер
COPY . .