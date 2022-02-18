
https://labs.play-with-docker.com/
https://training.play-with-docker.com/ops-stage1/

----------------------------------------
Commands:

 docker-compose up
 docker version
 docker ps  #Работающие контейнеры

 docker-compose stop # остановить контейнеры
 docker-compose rm # удалить контейнеры

docker search nginx #Поиск образа

docker create -t -i eon01/infinite --name infinite #Создание контейнера
docker run -it --name infinite -d eon01/infinite   #Первый запуск контейнера
docker rm infinite   #Удаление контейнера



-----------------------

https://phptoday.ru/post/gotovim-lokalnuyu-sredu-docker-dlya-razrabotki-na-php

October CMS Old version
composer create-project october/october yourNAMEofPROJECT 1.1.*