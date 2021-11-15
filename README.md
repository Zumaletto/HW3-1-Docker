## PostgreSQL
___

### Задача:
Необходимо подготовить приложение к тестированию на СУБД PostgreSQL.

### Описание действий:
1. В локальном репозитории создать:
- db-api.jar (приложение)
- application.properties( файл для хранения конфигурационных параметров приложения)
- docker-compose.yml(настройка для запуска контейнера PostgreSQL)
2. Запустить docker-compose.yml командой ```docker-compose up -d```. Дождаться запуска PostgreSQL.
3. Запустить приложение командой ```java -jar db-api.jar```.
4. Проверить результат путем запроса ```GET http://localhost:9999/api/cards```.

### Результат
![Desktop 2021-11-15 21-59-57](https://user-images.githubusercontent.com/87120177/141841782-70518971-e254-4a8a-b41e-46898129650d.png)

5. Остановить и удалить контейнер командой ```docker-compose down```.
