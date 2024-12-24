# Для запуска проекта, необходимо выполнить следующие шаги:

1. Склонировать репозиторий с клиентским приложением по ссылке https://github.com/Dmitriy-X-r/Nstugram.git на свой компьютер.
```
git clone https://github.com/Dmitriy-X-r/Nstugram.git
```

2. Склонировать репозиторий с api по ссылке [https://github.com/Dmitriy-X-r/express-threads-api.git](https://github.com/Dmitriy-X-r/express-threads-api.git) на свой компьютер.
```
git clone https://github.com/Dmitriy-X-r/express-threads-api.git
```

3. Открыть терминал (или командную строку) и перейти в корневую директорию сервера.
```
cd express-threads-api
```

4. Переименовать файл .env.local (убрать .local)
```
.env
```

5. Запустить команду docker compose которая поднимет сервер, клиент и базу данных
```
docker compose up
```

6. Открыть браузер и перейти по адресу http://localhost:80, чтобы увидеть запущенный проект.

