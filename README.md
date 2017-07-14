# django-rest-framework-tutorial
Source code for the Django REST framework tutorial. Own training.

## Installation
```shell
virtualenv -no-site-package .env
```
```shell
$ source .env/bin/activate 
```
```shell
(.env)$ pip install -r requirements.txt
```
```shell
(.env)$ python tutorial/manage.py makemigrations snippets
(.env)$ python tutorial/manage.py migrate
```
```shell
(.env)$ python tutorial/manage.py runserver
```
