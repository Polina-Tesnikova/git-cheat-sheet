# Шпаргалка по настройки GIT

## Инициализируем репозиторий

Сделать папку репозиторием — **git init**

«Разгитить» папку, если что-то пошло не так, **— rm -rf .git**

Проверить состояние репозитория — **git status**

---
## Добавляем файлы в репозиторий

Подготовить файлы к сохранению — **git add --all** (все файлы) или **git add .** (вся папка)

---
## Работаем с коммитами

Выполнить коммит —** git commit -m ‘Текст сообщения, что было сделано’**

Просмотреть историю коммитов — **git log**

---
# Настройка Github

1. [Регистрация](https://practicum.yandex.ru/learn/qa-automation-engineer-java/courses/4bec7a9a-7552-4f4f-9ef3-bfcaabfcaa55/sprints/882571/topics/e942bcd8-542f-4116-b71d-57cdd2d77cdb/lessons/06c23298-71d9-4654-aae7-0d896c536abe/)
2. [Создание удалённого репозитория](https://practicum.yandex.ru/learn/qa-automation-engineer-java/courses/4bec7a9a-7552-4f4f-9ef3-bfcaabfcaa55/sprints/882571/topics/e942bcd8-542f-4116-b71d-57cdd2d77cdb/lessons/eb76251c-cb55-4478-8ab8-b9cb71c8a7d8/)
3. [Генерация ssh-ключей](https://practicum.yandex.ru/learn/qa-automation-engineer-java/courses/4bec7a9a-7552-4f4f-9ef3-bfcaabfcaa55/sprints/882571/topics/e942bcd8-542f-4116-b71d-57cdd2d77cdb/lessons/634af282-8529-422d-a257-68ac6a51e8b0/)
4. [Привязка ssh-ключей к Github](https://practicum.yandex.ru/learn/qa-automation-engineer-java/courses/4bec7a9a-7552-4f4f-9ef3-bfcaabfcaa55/sprints/882571/topics/e942bcd8-542f-4116-b71d-57cdd2d77cdb/lessons/c8c707cd-b671-4297-b413-24726da654a6/)
5. [Связывание локального и удалённого репозитория](https://practicum.yandex.ru/learn/qa-automation-engineer-java/courses/4bec7a9a-7552-4f4f-9ef3-bfcaabfcaa55/sprints/882571/topics/e942bcd8-542f-4116-b71d-57cdd2d77cdb/lessons/b74f4a58-abfe-4b97-b72c-20446a0338dd/)
6. [Синхронизация репозиториев](https://practicum.yandex.ru/learn/qa-automation-engineer-java/courses/4bec7a9a-7552-4f4f-9ef3-bfcaabfcaa55/sprints/882571/topics/e942bcd8-542f-4116-b71d-57cdd2d77cdb/lessons/834cebd0-c3e3-4be8-a88d-d94bfe0bb8a7/)

---
# Язык разметки Markdown


Пример _курсива_, ещё *курсива* и **жирного текста**, и ещё один вид __жирного текста__


~~Зачёркнутый текст~~

Текст над чертой

---

Текст под чертой


Текст до переноса..
Текст после переноса с точками <br>
Текст после переноса с тегом

line,
not another line

---

line,

another line

-----

А вот список:
1. Нумерованный список
2. Нумерованный список

* ненумерованный со звёздочкой
* и ещё со звёздочкой

- ненумерованный с дефисом
- и опять с дефисом


А теперь попробуем ссылку
[Гугл-поиск](https://www.google.com/?hl=ru "Это Гугл!")


А теперь код!
```bash
ls - la
```
```html
<h1>А я просто текст</h1>
```
