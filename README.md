# django-bootcamp-portilla
Learn more about Django

```
conda create --name env django
activate env
deactivate env
```

## specific version of python of package
```
conda create --name env python=3.5
```

## check out the envs
```
conda info --envs
conda env list

```

## install package
```
conda install <package>
```

## Django project and Django application

```
django-admin
django-admin startproject first_project
```

wsgi - web server gateway interface
manage.py - build web project / application

```
python manage.py runserver
```

A Django project is a collection of applications and configurations
Pluggable Django application 

### Django application
```
python manage.py startapp first_app
```

### Django database migrations
```
python manage.py migrate
python manage.py makemigrations first_app
python manage.py migrate
python manage.py shell
```

shell commands
```
from first_app.models import Topic
t = Topic(top_name="Social Network")
t.save()
Topic.objects.all()

```

### Admin 
```
python manage.py createsuperuser
orange Charisma1234
```

# PIP freeze
```
pip list --format=freeze > ../requirements.txt
```

# Populate scripts with Faker

Not related to django but if you want to host a flask application to Github pages
you may want to use: 
https://pythonhosted.org/Frozen-Flask/ - github pages
https://www.pythonanywhere.com/pricing/


# Personal portfolio on github pages here 
https://codeburst.io/10-awesome-web-developer-portfolios-d266b32e6154




# DJango MTV ( Models-Templates-Views )

