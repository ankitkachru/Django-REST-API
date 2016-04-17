#API using Django REST

Works on Django 1.9 and Python 2.7 and above.

pip install django pip install djangorestframework django-admin.py startproject restexample .

*USE MIGRATE IN Django (1.9) and ./manage.py syncdb for older versions. Use ./migrate.py help for list of commands.*
./manage.py migrate
./manage.py createsuperuser

*to RUN*

./manage.py runserver

*FOR WINDOWS, USE curl in Windows PowerShell*
To view users
curl -H 'Accept: application/json; indent=4' -u admin:password http://127.0.0.1:8000/users/

To create user
$ curl -X POST -d username=new -d email=new@example.com -d is_staff=false -H 'Accept: application/json; indent=4' -u admin:password http://127.0.0.1:8000/users/

*DJANGO-REST-DOCUMENTATION* at http://www.django-rest-framework.org
