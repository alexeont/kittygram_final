![example workflow](https://github.com/alexeont/kittygram_final/actions/workflows/main.yml/badge.svg?event=push)

##  Описание проекта Kittygram:

на сайте можно посмотреть на котиков,
а залогиненные пользователи могут оставлять карточки с фотографиями и достижениями своих питомцев

## Cтек технологий:

Python 3.9 as programming language
Django 3.2 as web framework
Django REST framework 3.12 as toolkit for building Web APIs
POSTGRESQL as database
GitHub as repo and workflows manager
Docker as deploy and containerization service

## Установка:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/alexeont/kittygram_final
cd kittygram_final
```

Cоздать и активировать виртуальное окружение:

```
cd backend
python -m venv venv
```

```
source venv/Scripts/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Создать файл зависимостей среды .env в корне проекта. Образец -- .env.example


## Запуск проекта на удаленном сервере:

В своем репозитории на GitHub в разделе настроек добавить необходимые секреты для файла .github/workflows/main.yml
Перенести в папку проекта на сервере файл .env
Запушить проект на гит, чтобы запустить процесс автоматического деплоя

Автор проекта: Александр Леонтьев
