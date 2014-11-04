# thinkster-django-angular-boilerplate

## Installation

*NOTE: Requires [virtualenv](http://virtualenv.readthedocs.org/en/latest/),
[virtualenvwrapper](http://virtualenvwrapper.readthedocs.org/en/latest/) and
[Node.js](http://nodejs.org/).*

* Fork this repository.
* `$ git clone git@github.com:<your username>/thinkster-django-angular-boilerplate.git`
* `$ mkvirtualenv thinkster-djangular`
* `$ cd thinkster-django-angular-boilerplate/`
* `$ pip install -r requirements.txt`
* `$ npm install`
* `$ bower install`
* `$ python manage.py migrate`
* `$ python manage.py runserver`

## Deployment

*NOTE: Requires [Heroku Toolbelt](https://toolbelt.heroku.com/).*

* `$ heroku apps:create`
* `$ heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git`
* `$ heroku config:set DEBUG=False`
* `$ heroku config:set COMPRESS_ENABLED=True`
* `$ git push heroku master`
* `$ heroku open`
