Django Boilerplate
===========================

This is a simple boilerplate for django projects

### Usage

This assumes you have pip and django 1.10 installed (if not, try `$ pip install django==1.10`)

    $ django-admin.py startproject --template https://github.com/guilouro/django-boilerplate/archive/master.zip my_project .
    $ pip install -r requirements.txt
    $ python manage.py migrate

#### Packages Required
- **[Unipath]**: An object-oriented approach to file/directory operations
- **[dj-database-url]**: Allows you to utilize the [12factor](http://www.12factor.net/backing-services) inspired `DATABASE_URL` environment variable to configure your app.


[Unipath]: https://github.com/mikeorr/Unipath
[dj-database-url]: https://github.com/kennethreitz/dj-database-url
