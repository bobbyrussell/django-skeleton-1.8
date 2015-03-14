#{{ project_name|title }}
## About
This is a very simple django 1.7 skeleton project. The project structure was
influenced by [Two Scoops](http://twoscoopspress.org/), which is sadly no
longer being revised for versions beyond 1.6.
## Requirements
* Bower
* Django 1.7
## Installation
* Create a virtualenv
* Install django
* Invoke:

        virtualenv env
        . env/bin/activate
        pip install django
        django-admin.py startproject --template=https://github.com/bobbyrussell/django-skeleton-1.7/archive/master.zip --extension=py,md,html,json,.bowerrc <project name>
        cd <project name>
        bower install
## License
This code is licensed under the MIT License.
