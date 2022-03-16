# Django eLog App

-----------------------------------------------------------------

Learning Log—is an online journal system that lets you keep track of information about python topics.

### Creating a new project
```
django-admin startproject project_name .
```
- Create Database Migration
```
python manage.py migrate
```
- Run Server
```
python manage.py runserver
```
- Start new application & run migration
```
python manage.py startapp app_name
python manage.py makemigrations app_name
python manage.py migrate
```

## Django Admin
### Setting Up a Superuser
- Run the code in your terminal:
```
python manage.py createsuperuser
```

## Running Django Shell
```
python manage.py shell
```