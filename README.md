Задача на Python

Этот проект представляет собой простое сетевое приложение, написанное на Python с использованием асинхронного программирования. Приложение состоит из сервера и двух клиентов, которые общаются между собой, обмениваясь сообщениями.

Описание

Сервер и клиенты создают асинхронные сетевые соединения и обмениваются сообщениями через TCP/IP протокол. Клиенты отправляют серверу сообщения "PING", а сервер отвечает на них сообщением "PONG". Взаимодействие между клиентами и сервером осуществляется с использованием асинхронной библиотеки asyncio.

Установка
1. Склонируйте репозиторий на локальную машину:
git clone https://github.com/Morf-P/simple-network-app.git
   
2. Перейдите в директорию проекта:
cd simple-network-app
Запустите сервер:
python server.py

2. Запустите два клиента:

python client.py

python client.py

Примечания
- Убедитесь, что сервер запущен перед запуском клиентов.
- По умолчанию, сервер запускается на `127.0.0.1:8888`. Вы можете изменить адрес и порт в коде, если это необходимо.
