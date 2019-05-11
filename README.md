# First Django App with django-tastypie REST framework

### Create App
Run the following
```shell
$ django-admin startproject <project_name>
$ cd <project_name>
$ python manage.py startapp <app_name>
```

*NOTE: add the following to `<project_name>/settings.py` `INSTALLED_APPS` list*
- '<app_name>'
- 'django_seed'


### References
1) https://codeburst.io/create-a-django-api-in-under-20-minutes-2a082a60f6f3
2) Seeding: https://pypi.org/project/django-seed/

### Start App
Run the following
```shell
$ python manage.py runserver
```

### Access Django Console
Run the following
```shell
$ python manage.py shell
```

To interact with a model through the console run the following
```shell
$ python manage.py shell
>>> from api.models import <model_name>
```
### Migrations

#### Create
1) Add models to `api/models.py`
2) Run the following
```shell
$ python manage.py makemigrations
```

### Run
Run the following
```shell
$ python manage.py migrate
```
