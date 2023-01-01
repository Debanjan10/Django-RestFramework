# Django-RestFramework
This is a basic api project  to learn django Rest Framework.I am writing this guide taking into considerations that you know how django works.

First you should have a running interpreter of python in your computer system.
I use pycharm community edition as it is free to use.
Create a project in python then install django inside the directory using
pip install django

then use 
django-admin startproject to create a django project
use python manage.py runserver to check if the server is working properly.
next create a django-app inside the django-project directory using the following command
python manage.py startapp myapi
myapi is the name of the app we created.
Next we have to register this app inside the installed app section inside settings.py
Next create models views and urls for the app in views.py, urls.py and models.py section respectively.
use command pip install django-restframework to install this open source framework
create superuser using django
register your model in admin.py
add hero names and their aliases inside the admin page we just created using django.
run migrations and migrate for the databases.

