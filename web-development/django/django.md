Django
======

#### dependencies

    $ sudo apt-get install python-pip python-dev build-essential 
    $ sudo pip install --upgrade pip 
    $ sudo apt-get install libpq-dev python-dev

#### Installation

    $ pip install django

#### Create Project

    $ django-admin.py startproject [PROJECT]
    

#### Run server

on Cloud9

    $ python manage.py runserver $IP:$PORT
    
    
#### Create Application

    $ python manage.py startapp [APP]

Register app with project

    $ nano [PROJECT]/settings.py

```python

INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    '[APP]',
]

```
