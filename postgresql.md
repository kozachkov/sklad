---
lang: ru
layout: home
lang-ref: postgresql
---

## PostgreSQL

[https://www.postgresql.org](https://www.postgresql.org/)

Полные руководства для разных выпусков [здесь](https://www.postgresql.org/docs/).

## Скопление складов (database cluster)

Место на накопителе, где, собственно, расположены данные по каждому складу.

Обычно расположено в:

- /usr/local/pgsql/data
- /var/lib/pgsql/data
- /var/lib/postgresql/{11}/main

### Создать скопление складов

Можно с помощью initdb, который поставляют вместе с PostgreSQL.

## Запасы

Пользователям с правами чтения к скоплению складов следует сохранять данные
оттуда в качестве запасов.

### Склады

#### Служебные

- postgres
- template1

#### Пользовательские

Которые пользователь создаёт сам явно.
