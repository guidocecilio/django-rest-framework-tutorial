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

To create a few users, to use for testing the API use the createsuperuser command
```shell
(.env)$ python manage.py createsuperuser

Running the server
```shell
(.env)$ python tutorial/manage.py runserver
```
