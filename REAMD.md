# Base Django Codyhouse

run ./get_codyhouse.sh

pyenv virtualenv [projectname]
pyenv local [projectname]

pip install wheel
pip install pip --upgrade
pip install django[verion]

django-admin startproject [name]
./manage.py migrate
./manage.py createsuperuser
./manage.py runserver 0:8000