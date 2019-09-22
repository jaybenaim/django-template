A django template, with authentication implemented. 

1. Start a new project
$ mkdir new-project 
2. cd into new-project 
3. activate virtual environment 
4. django-admin startproject new-app and cd into new-app
5. fork and clone this repo into new-app 
6. git clone https://github.com/jaybenaim/django-template.git .
7. cp django-template/ new-app

cd django-template 
rm -rf .git (or in Windows rmdir .git /S /Q) - Remove Git database
git init - Initialize a new Git repository
git add . - Add all files to staging
git commit -am "Initial commit" - Commit the files


1. In views.py 
    from <Your-app-name >.models import *

2. python manage.py makemigrations <Your-app-name>

3. python manage.py migrate 

4. python manage.py runserver 

