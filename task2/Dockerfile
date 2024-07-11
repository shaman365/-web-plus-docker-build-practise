FROM node:16-alpine

# создание директории приложения
WORKDIR /home/ilovedocker/app

# установка зависимостей
# астериск ("*") по возможности скопирует оба файла: package.json и package-lock.json
# тот же символ делает копирование опциональным, т. е. без файла сборка не упадёт
COPY hello.sh ./


ENTRYPOINT sh 