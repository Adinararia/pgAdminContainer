СУБД PgAdmin в контейнере

Отдельно создается контейнер с pgAdmin к которому можно коннектить бд

Установка

1. Установить Docker и Docker-compose
2. docker network create pg-admin-network
3. docker-compose up -d
4. Добавить для контейнеров в которых лежат база сеть pg-admin-network
