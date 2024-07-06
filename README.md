# django_recipes2.0 🍽️

## Описание 📖
**django_recipes2.0** - это проект на Django, который позволяет пользователям создавать, просматривать и управлять рецептами. Проект включает в себя несколько приложений: `myrecipesite`, `recipes` и `users`.

## Установка 🛠️
Для локальной установки проекта выполните следующие шаги:

1. **Клонирование репозитория:**
    ```bash
    git clone https://github.com/nasirovx/django_recipes2.0.git
    cd django_recipes2.0
    ```

2. **Создание виртуального окружения:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Для Windows используйте `venv\Scripts\activate`
    ```

3. **Установка зависимостей:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Применение миграций:**
    ```bash
    python manage.py migrate
    ```

5. **Запуск сервера разработки:**
    ```bash
    python manage.py runserver
    ```

## Использование 💻
Перейдите в браузер по адресу [http://127.0.0.1:8000/](http://127.0.0.1:8000/) и начните использовать приложение. Вы можете создавать рецепты, просматривать их и управлять пользователями.

## Функциональные возможности 🚀
- Создание и редактирование рецептов 📝
- Управление пользователями 👤
- Просмотр списка рецептов 📋

## Структура проекта 🗂️
django_recipes2.0/
│
├── myrecipesite/
│ ├── pycache/
│ ├── init.py
│ ├── asgi.py
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│
├── recipes/
│ ├── pycache/
│ ├── migrations/
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── forms.py
│ ├── models.py
│ ├── tests.py
│ ├── urls.py
│ ├── views.py
│
├── static/
│ ├── css/
│ ├── img/
│ ├── templates/
│ ├── recipes/
│ ├── users/
│
├── users/
│ ├── pycache/
│ ├── migrations/
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── views.py
│
└── manage.py



## Технологии 🛠️
Проект написан с использованием следующих технологий:
- Django
- Python
- HTML/CSS
- JavaScript

## Вклад в проект 🤝
Если вы хотите внести свой вклад в проект, пожалуйста, создайте pull request или откройте issue для обсуждения.

## Авторы ✨
- [nasirovx](https://github.com/nasirovx)

## Лицензия 📄
Этот проект лицензирован по [MIT License](LICENSE).

[![GitHub issues](https://img.shields.io/github/issues/nasirovx/django_recipes2.0)](https://github.com/nasirovx/django_recipes2.0/issues)
[![GitHub forks](https://img.shields.io/github/forks/nasirovx/django_recipes2.0)](https://github.com/nasirovx/django_recipes2.0/network)
[![GitHub stars](https://img.shields.io/github/stars/nasirovx/django_recipes2.0)](https://github.com/nasirovx/django_recipes2.0/stargazers)

Создание активного репозитория также включает в себя регулярные коммиты, участие в обсуждениях и решении issues. Не забывайте документировать все изменения в вашем проекте и вести активное общение с пользователями и разработчиками.
