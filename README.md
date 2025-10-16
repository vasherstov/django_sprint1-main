# Blogicum
Проект **blogicum** — учебный проект на Django, реализующий блог с постами и категориями.  
Позволяет просматривать список постов, детали каждого поста и фильтровать их по категориям.

---

## 📂 Структура проекта

django_sprint1-main/

├── blogicum/ # Основная директория проекта Django

│ ├── blog/ # Приложение для работы с постами

│ │ ├── migrations/ # Миграции базы данных

│ │ ├── init.py

│ │ ├── admin.py

│ │ ├── apps.py

│ │ ├── models.py

│ │ ├── tests.py

│ │ ├── urls.py

│ │ └── views.py

│ ├── pages/ # Приложение для статических страниц

│ │ ├── migrations/

│ │ ├── init.py

│ │ ├── admin.py

│ │ ├── apps.py

│ │ ├── models.py

│ │ ├── tests.py

│ │ ├── urls.py

│ │ └── views.py

│ ├── static_dev/ # Статические файлы проекта

│ │ ├── css/

│ │ └── img/

│ ├── templates/ # HTML-шаблоны

│ │ ├── base.html

│ │ ├── blog/

│ │ ├── includes/

│ │ └── pages/

│ ├── pycache/

│ ├── asgi.py

│ ├── settings.py

│ ├── urls.py

│ ├── wsgi.py

│ └── init.py

├── db.sqlite3 # База данных SQLite (игнорируется в git)

├── manage.py # Скрипт управления проектом Django

├── tests/ # Тесты проекта

│ ├── pycache/

│ ├── conftest.py

│ ├── test_files.py

│ ├── test_html.py

│ ├── test_settings.py

│ ├── test_templates.py

│ ├── test_urls.py

│ └── test_views.py

├── .flake8 # Конфигурация Flake8

├── .gitignore # Игнорируемые файлы и папки

├── LICENSE

├── README.md

├── requirements.txt # Список зависимостей

└── pytest.ini # Конфигурация pytest