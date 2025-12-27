# Template Django Project

## Структура проєкту
```commandline
template_django
|
⊢ app
    |
    ⊢ migrations
        ⊢ __init__.py
    |
    ⊢ admin.py
    ⊢ apps.py
    ⊢ models.py
    ⊢ tests.py
    ⨽ views.py
|
⊢ media
⊢ project
    |
    ⊢ admin.py
    ⊢ apps.py
    ⊢ models.py
    ⊢ urls.py
    ⨽ wsgi.py
|
⊢ static
    |
    ⊢ css
        ⨽ styles.css
    |
    ⊢ img
    |
    ⨽ js
        ⨽ sctipt.js
|
⊢ templates
    ⨽ index.html
|
⊢ manage.py
⊢ README.md
⨽ requiremenets
```

1. Встановити (або активувати) віртуальне середовище
2. Встановити залежності  
```pip freeze -r requirements.txt```
Другий метод
```uv freeze -r requirements.txt```
3. 