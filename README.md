# Сборка Docker-compose для Kandoard, Gitblit, Jenkins  

Включает следующие технологии: 

- Система управления задачами [Kanboard](https://kanboard.org/) 

- Система управления репозиториями [Gitblit](http://gitblit.github.io/gitblit/) 

- Система непрерывной интеграции [Jenkins](https://www.jenkins.io/)

## Настройка для Debian

1. Установить [docker](https://docs.docker.com/engine/install/debian/).
2. Установить [docker-compose](https://docs.docker.com/compose/install/).
3. Клонировать этот репозиторий

## Использование

Запустить проект:

    docker-compose up

Остановить выполнение: 

    docker-compose down 

Сервисы будут доступны по следующим ссылкам:  

- Kanboard: [http://localhost:80](http://localhost:80) 
- Gitblit: [http://localhost:8080](http://localhost:8080)
- Jenkins: [http://localhost:8081](http://localhost:8081)
