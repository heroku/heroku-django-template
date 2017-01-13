# Heroku Django Starter Template

An utterly fantastic project starter template for Django 1.10.

## Features

- Production-ready configuration for Static Files, Database Settings, Gunicorn, etc.
- Enhancements to Django's static file serving functionality via WhiteNoise.
- Latest Python 3.6 runtime environment.

## How to Use

To use this project, follow these steps:

1. Create your working environment.
2. Install Django (`$ pip install django`)
3. Create a new project using this template

## Creating Your Project

Using this template to create a new Django app is easy:

    $ django-admin.py startproject --template=https://github.com/heroku/heroku-django-template/archive/master.zip --name=.env,Procfile helloworld

You can replace ``helloworld`` with your desired project name.

## Deployment to Heroku

```sh
git init
git add -A
git commit -m "Initial commit"

heroku create
git push heroku master

heroku run python manage.py migrate
```

or

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

See also, a [ready-made application](https://github.com/heroku/python-getting-started), ready to deploy.

## Using Python 2.7?

Just update `runtime.txt` to `python-2.7.13` (no trailing spaces or newlines!).

## Further Reading

- [Gunicorn](https://warehouse.python.org/project/gunicorn/)
- [WhiteNoise](https://warehouse.python.org/project/whitenoise/)
- [django-environ](https://github.com/joke2k/django-environ/)
- [Python on Heroku](https://devcenter.heroku.com/categories/python)
