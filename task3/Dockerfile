FROM node:16-alpine

# создание директории приложения
WORKDIR /home/ilovedocker/app

COPY packages/package*.json /home/ilovedocker/app

RUN npm i

COPY src/* /home/ilovedocker/app

EXPOSE 3032

ENTRYPOINT [ "node", "main.js" ]