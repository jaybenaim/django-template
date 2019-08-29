A django template, with authentication implemented. 

1. In the settings folder change the following lines: 

    INSTALLED_APPS = [
        ... 
        'django.contrib.messages',
        'django.contrib.staticfiles',
        '<Your app name >'

    ROOT_URLCONF = '<Your app name >.urls'
    WSGI_APPLICATION = '<Your-app-name >.wsgi.application'

2. In views.py 
    from <Your-app-name >.models import *

2. python manage.py makemigrations <Your-app-name>

3. python manage.py migrate 

4. python manage.py runserver 

