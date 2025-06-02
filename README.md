# django_project

## Django commands

### Creating a project

In the terminal to start a project type "django-admin startproject project_name directory_name".

django-admin startproject my_project .


#### Project completes

When the project is created, the directory structure similar to the following:

```
manage.py
my_project/
├── __init__.py
├── settings.py
├── urls.py
├── asgi.py
└── wsgi.py
```


### Creating an app

To create a app in django go to the terminal and type:

`python manage.py startapp hello_world`

When this is created you will see files such as:

```
hello_world
├── __init__.py
├── admin.py
├── views.py
├── models.py

```
