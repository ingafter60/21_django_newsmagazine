# BUILDING A NEWS MAGAZINE APP USING DJANGO V2.2.5
https://github.com/ingafter60/21_django_newsmagazine
https://www.udemy.com/course/python-django-tkinter-complete-bundle-advance/learn/lecture/16516276#overview

## SECTION 21: Django 02 Run first web site


### 00. Initial commit

        new file:   .gitignore
        new file:   README.md

### 97. Install and Run Venv and Django

        > python3 -m venv venv38225
        > source venv3825/bin/activate
        > pip install django==2.2.5
        modified:   README.md

### 98. First Website

        > django-admin startproject myproject .
        modified:   README.md
        new file:   manage.py
        new file:   myproject/__init__.py
        new file:   myproject/settings.py
        new file:   myproject/urls.py
        new file:   myproject/wsgi.py 
              
### 99. Django Settings

        modified:   README.md
        new file:   db.sqlite3
        modified:   myproject/settings.py

### 100. Django Urls

        modified:   README.md
        modified:   myproject/urls.py

### 101. Default Django Admin

        modified:   README.md
        modified:   db.sqlite3



## SECTION 22: Django 03 Start app


### 102. Start App - Create an app 'main', register it and urls 

        modified:   README.md
        new file:   main/admin.py
        new file:   main/apps.py
        new file:   main/models.py
        new file:   main/tests.py
        new file:   main/urls.py
        new file:   main/views.py
        modified:   myproject/settings.py
        modified:   myproject/urls.py

### 103-105. Create templates, views and urls to display Hello World!

        modified:   README.md
        new file:   main/templates/home.html
        modified:   main/urls.py
        modified:   main/views.py

### 106. Register App