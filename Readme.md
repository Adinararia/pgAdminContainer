СУБД PgAdmin в контейнере

Отдельно создается контейнер с pgAdmin к которому можно коннектить бд
Install

1. Установить докер и докер композ
2. docker-compose up -d
3. docker network create pg-admin-network
4. Добавить для контейнеров в которых лежат база сеть pg-admin-network
