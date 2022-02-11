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
![Снимок экрана (17)](https://user-images.githubusercontent.com/82859085/153580387-05ba935e-ca21-494f-9571-8650b73b3c40.png)
![Снимок экрана (14)](https://user-images.githubusercontent.com/82859085/153580414-233380d4-c02c-48cc-91d3-14e55e433d2e.png)
![Снимок экрана (15)](https://user-images.githubusercontent.com/82859085/153580471-0d0b08f8-1310-47ff-a9c8-b032ad365450.png)
![Снимок экрана (16)](https://user-images.githubusercontent.com/82859085/153580483-31e1db2e-7f9f-49a8-bb76-e1563d8af4f4.png)

