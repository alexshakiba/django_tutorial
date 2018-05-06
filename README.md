# Django Tutorial Notes

### To start new project
1. Navigate to root folder where you create django app
2. run ```django-admin startproject mysite``` in terminal
3. run app: navigate to project root folder and run ```python manage.py runserver```
4. URL to view: http://127.0.0.1:8000/polls/

### Create Poll APP
Run in root directory terminal ```python manage.py startapp polls```

### Create/Update db tables for installed apps
Run ```python manage.py migrate``` in terminal

### Create/Update new model
Model: Single definitive source of truth of data to include:
- data type
- data length
- data name

To see what needs to be migrated: ```python manage.py makemigrations polls```
<br>
To run actual migration and create new tables in db: ```python manage.py migrate```

### Create/Django Admin:
Run ```python manage.py createsuperuser``` and create username and password

### Run program shell for testing:
Run ```python manage.py shell``` in terminal

#Run testing Scripts:
```python manage.py test polls``` <- polls refers to the app name

[Link to Django Project Tutorial](https://docs.djangoproject.com/en/2.0/intro/tutorial01/)
