> [!IMPORTANT]
>
> ⚛️ **[Все задачи](TODO.md), которые мы делаем.** Вдруг кто забыл :) ⚛️
>  

# Agile Health Hackathon
* [Расписание хакатона](https://impulse.t1.ru/hackathons/saint_petersburg_2024)
* [Личный кабинет](https://spb.hackathon-t1.ru/todo) (у каждого свой)
* [Слайды с описанием задачи](https://docs.google.com/presentation/d/1Ixn7mnErgfvu0Kuxk7OUIWIuMWP2KfNRwGEyVObvuwI/edit#slide=id.g3141d0e0588_0_411)

**Технологический стек:** Java + фреймворк [Jmix](https://www.jmix.ru) • PostgreSQL • [Docker](https://www.docker.com) • Python + (?) Pandas

### Запуск проекта

- Клонируйте репозиторий с GitHub

- Скачайте и установите JDK 17 для своей ОС на сайте Eclipse [по этой ссылке](https://adoptium.net/temurin/releases/)

- Выполните команду сборки:

```shell
# Очистка проекта
# Linux или macOS
./agile-health/gradlew clean --project-dir ./agile-health

# Windows
./agile-health/gradlew.bat clean --project-dir ./agile-health

# Сборка проекта
# linux or mac os
./agile-health/gradlew -Pvaadin.productionMode=true bootJar --project-dir ./agile-health

# windows 
./agile-health/gradlew.bat -Pvaadin.productionMode=true bootJar --project-dir ./agile-health
```

- Установите Docker Desktop с [официального сайта](https://www.docker.com/products/docker-desktop/)

- Запустите все контейнеры docker-compose следующей командой:
```shell
docker compose up -d
```

- Чтобы войти в систему "Agile Health" перейдите по ссылке [http://localhost:8080](http://localhost:8080). Логин: "admin", пароль: "admin".
