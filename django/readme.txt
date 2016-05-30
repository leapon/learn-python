Install Django
--------------

pip install django


$ python
Python 2.7.11 (default, Mar  8 2016, 19:34:05) 
[GCC 4.2.1 Compatible Apple LLVM 7.0.2 (clang-700.1.81)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import django
>>> print(django.get_version())
1.9.6
>>> 


Django Document

https://docs.djangoproject.com/en/1.9/intro/install/


Create Website
--------------

$ django-admin startproject dsite

$ cd dsite

$ python manage.py runserver
Performing system checks...

System check identified no issues (0 silenced).

You have unapplied migrations; your app may not work properly until they are applied.
Run 'python manage.py migrate' to apply them.

May 30, 2016 - 15:19:36
Django version 1.9.6, using settings 'dsite.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
Not Found: /
[30/May/2016 15:19:44] "GET / HTTP/1.1" 200 1767
Not Found: /favicon.ico
[30/May/2016 15:19:44] "GET /favicon.ico HTTP/1.1" 404 1935

