#{{ project_name|title }}
## About
This is a very simple django 1.8 skeleton project. The project structure was
influenced by [Two Scoops](http://twoscoopspress.org/), which, sadly, is no
longer being revised for versions of Django beyond 1.6.
## Requirements
* Bower
* Django 1.8

[Bower](http://bower.io/) allows us to manage our jQuery and Bootstrap assets
easily. We need Django installed in order to use `django-admin.py` to build a
project from the template.
## Installation
* Invoke:

        virtualenv env
        . env/bin/activate
        pip install django
        django-admin.py startproject \
            --template=https://github.com/bobbyrussell/django-skeleton-1.8/archive/master.zip \
            --extension=py,md,html,json,.bowerrc <project name>
        cd <project name>
        pip install -r requirements/base.txt
        bower install
        python manage.py runserver
* Point your browser to [http://localhost:8000/](http://localhost:8000)

`virtualenv env` creates a [virtualenv](https://virtualenv.pypa.io/en/latest/)
in the `env` directory, and `. env/bin/activate` sources the virtualenv into
the current shell. `pip install django` will then install django to your
virtualenv. `django-admin.py` is then used to create a project from the
django-skeleton-1.7 template.

`cd` into the project's working directory and `pip install -r requirements/base.txt` 
the rest of the python requirements into the virtualenv. `bower install` will 
pull down the frontend dependencies. Finally, we can run
`python <project_name>/manage.py runserver`.

After installation, you can start hacking right away!
## License
This code is licensed under the MIT License.
