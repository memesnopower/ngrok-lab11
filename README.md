# Лабораторная работа №11

Установим ngrok через: wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-386.tgz

Разархивируем архив: tar -xf ngrok-v3-stable-linux-386.tgz

Подключим токен: ./ngrok config add-authtoken ...


Установим python: 

sudo apt install python3 -y

sudo apt install python3-pip -y

Создадим папку и сделаем там файл > index.html, а также пропишем python3 -m http.server для запуска локального сервера

Запустим ngrok: ./ngrok http 8000 

![image](https://user-images.githubusercontent.com/115490701/235741848-505202c6-ec80-4974-ad46-a991fc519642.png)

И для подключения к нашему серверу скопируем ссылку, которая находиться напротив forwarding

