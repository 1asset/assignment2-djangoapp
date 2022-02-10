# Assignment 2 - Blockchain analytics tool using Django

It's the assignment 2 from the Python 2 course, that requires a Blockchain analytics tool using Django

# Installation

```bash
pip install Django
```

```bash
pip install migrate
```

Install pgAdmin
Install for both desktop and web modes:
```bash
sudo apt install pgadmin4
```
Install for desktop mode only:
```bash
sudo apt install pgadmin4-desktop
```
Install for web mode only: 
```bash
sudo apt install pgadmin4-web 
```
Configure the webserver, if you installed pgadmin4-web:
```bash
sudo /usr/pgadmin4/bin/setup-web.sh
```

# Usage
```bash
django-admin startproject django_chart_app
```

```bash
python manage.py startapp chartapp
```

```bash
python manage.py runserver
```

```bash
python manage.py makemigrations chartapp
```

```bash
python manage.py sqlmigrate chartapp
```

```bash
python manage.py migrate
```

# Examples
