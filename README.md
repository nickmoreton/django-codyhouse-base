# Django Codyhouse Base

Quickly get codyhouse in place for a django project

## Getting Started

### Dependencies

https://github.com/CodyHouse/codyhouse-framework

### Installing Cody House

* run ./get_codyhouse.sh

### Installing Django

```
pyenv virtualenv [projectname]
pyenv local [projectname]
pip install wheel
pip install pip --upgrade
pip install django[version]
```

### Set Up Django

```
django-admin startproject [name]
./manage.py migrate
./manage.py createsuperuser
./manage.py runserver 0:8000
```