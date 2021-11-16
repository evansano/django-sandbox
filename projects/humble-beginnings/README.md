# First site
Following Django polling application tutorial

Source: https://docs.djangoproject.com/en/3.2/intro/tutorial01/

## Initialization
```
$ pip install -r requirements.txt
$ django-admin startproject mysite
$ # Root directory container name does not matter.
$ # Using this command to stress that fact.
$ mv mysite site
```

## Run Development Server
```
$ cd site
$ python manage.py runserver
```

## Add Polls Application
```
$ python manage.py startapp polls
```

