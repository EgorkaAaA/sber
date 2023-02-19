 # Тестовое задание
 ## Основная информация о проекте:

- Java 17
- Maven
- Все модули сделаны при помощи Spring boot

## Клиент:

### Переменные среды:

- SERVER_PORT:8081 - порт, на котором будет запущено приложение;
- BACK_URL:http://localhost:8080 - адрес, на котором расположен сервер;
- THREAD:5 - количество потоков, в которых будут запросы на сервер;
- AIRPORTS_COUNT:500 - количество потоков, в которых будут запросы на backend.

### Команда запуска:

```
java -jar client-0.0.1-SNAPSHOT.jar --THREAD=2 --AIRPORTS_COUNT=10
```

### Ссылка на jar: [ссылка](https://drive.google.com/file/d/146SpQpNW_3KhfvQ2T-mnQ4Xa8Yjanv-v/view?usp=share_link)

## Сервер:

### Переменные среды:

- SERVER_PORT:8080 - порт, на котором будет запущено приложение;

### Сборка:

```
mvn clean install
```
###  Запуск:

```
mvn -pl back exec:java
```


