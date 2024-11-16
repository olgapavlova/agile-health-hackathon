# Agile Health Hackathon
* [Расписание хакатона](https://impulse.t1.ru/hackathons/saint_petersburg_2024)
* [Личный кабинет](https://spb.hackathon-t1.ru/todo) (у каждого свой)
* [Слайды с описанием задачи](https://docs.google.com/presentation/d/1Ixn7mnErgfvu0Kuxk7OUIWIuMWP2KfNRwGEyVObvuwI/edit#slide=id.g3141d0e0588_0_411)

## Технологический стек
* Java
* Фреймворк [Jmix](https://www.jmix.ru)
* PostgreSQL
* Docker
* (?) Python
* (?) Pandas

### Запуск проекта

- Клонируйте репозиторий с GitHub

- Скачайте и установите JDK 17 для своей ОС на сайте Eclipse [по этой ссылке](https://adoptium.net/temurin/releases/)

- Выполните команду сборки:

```shell
# linux or mac os
./agile-health/gradlew bootJar --project-dir ./agile-health

# windows 
./agile-health/gradlew.bat bootJar --project-dir ./agile-health
```

- Установите Docker Desktop с [официального сайта](https://www.docker.com/products/docker-desktop/)

- Запустите все контейнеры docker-compose следующей командой:
```shell
docker compose up -d
```

- Чтобы войти в систему "Agile Health" перейдите по ссылке [http://localhost:8080](http://localhost:8080). Логин: "admin", пароль: "admin".

## ToDo
### Next Strep (до утра субботы)
 - [ ] РГ Развернуть среду (Docker, PostgreSQL,…)
 - [ ] РГ Собрать скелет системы
 - [ ] ЛН Рассчитать метрики по [ТЗ](https://docs.google.com/presentation/d/1Ixn7mnErgfvu0Kuxk7OUIWIuMWP2KfNRwGEyVObvuwI/edit#slide=id.g3141d0e0588_0_411) (хоть в Excel)
 - [ ] ОП Посмотреть в сторону UI kit'а и его возможностей
 - [ ] ОП Посмотреть, какие нужны будут SQL-запросы для метрик
 - [ ] ВЗ Выяснить судьбу Оли М.

> [!IMPORTANT]
> **Сверка по итогам вечера-ночи-утра →** Суббота, 16 ноября • 🕤 09:30–09:55 • https://meet.google.com/otw-aydf-ctr

> [!CAUTION]
> **Первый checkpoint →** Суббота, 16 ноября • 🕙 10:10–10:20 • ссылку пришлют в Telegram-канал
> _Подключаться в формате «Название команды | Фамилия Имя»_

### Полировка
 - [ ] Demo-видео продукта
 - [ ] ReadMe для установки
 - [ ] Публичный код, готовый к развёртыванию
