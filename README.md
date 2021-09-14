# Тестовое задание API опросов

## Как запустить
### Первоначальная установка 
```
cd Test-task-API
pip install -r requirements.txt
cd backend
python manage.py migrate
python manage.py createsuperuser
```
Создаём супер-юзера с именем admin и паролем admin.
Это имя и пароль будут использоваться в тестах (см. tests/settings.py).

### Запуск сервера
```
cd Test-task-API/backend
python manage.py runserver
```

## Описание API

См. [API.md](API.md)
