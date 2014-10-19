django-symposion-template
=====================

A starter project demonstarting a minimal symposion instance. Supports Django 1.7+

Based on [pinax-project-symposion](https://github.com/pinax/pinax-project-symposion) and using my forked version of [symposion](https://github.com/iambibhas/symposion).

Usage:

    django-admin.py startproject --extension=py,json --template=https://github.com/iambibhas/django-symposion-template/zipball/master <project_name>

Getting Started:

    pip install virtualenv
    virtualenv mysiteenv
    source mysiteenv/bin/activate
    pip install Django
    django-admin.py startproject --extension=py,json --template=https://github.com/iambibhas/django-symposion-template/zipball/master mysite
    cd mysite
    pip install -r requirements.txt
    python manage.py syncdb --no-initial-data
    python manage.py loaddata fixtures/*
    python manage.py runserver
