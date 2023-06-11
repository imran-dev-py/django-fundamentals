![Language](https://img.shields.io/badge/Python-v3.10.x-important)&nbsp;
![Django](https://img.shields.io/badge/Django-v4.2.x-important)&nbsp;
![Update](https://img.shields.io/badge/Last%20Update-June%2011,%202023-brightgreen)&nbsp;
![Completed](https://img.shields.io/badge/Progress-46/111-important)&nbsp;

- Pipenv Doc — https://pipenv-fork.readthedocs.io/
- [Pipenv: The Future of Python Dependency Management](https://www.youtube.com/watch?v=GBQAKldqgZs) — PyCon 2018

## Installation via Virtualenv

- Go to the directory and type `pip install pipenv`.
- After installed successfully type `pipenv install` to create virtualenv.
- For activate the virtualenv type `pipenv shell`.
- To install django type `pipenv install django` | `pipenv install django==x.x.x`.
- To check is there any available virtualenv for this current project type `pipenv --venv` & if it is existed then will display the location of the virtualenv else return message.
- To exit the virtualenv type `exit` or `CTRL + d` & terminal will back to normal prompt.
- Create Django project `django-admin startproject "NameOfProject" .`.
- Create django app `python manage.py startapp "NameofApp"`.
- Migration command `python manage.py makemigrations` then `python manage.py migrate`.
- Remove virtualenv `pipenv --rm`. It will delete virtualenv for this current project.
- Create `requirements.txt` file type `pip freeze > requirements.txt`.
- Install all dependencis after clone the repo type `pipenv install` then `pipenv install -r requirements.txt`.
- Check Django version `python -m django --version`.

## Tricks/Cheatsheet

- [Classy Class-Based Views](https://ccbv.co.uk/)
- [Classy Django REST Framework](https://www.cdrf.co/)
- [Classy Django Forms](https://cdf.9vo.lt/)
- [adamghill/django-fbv](https://github.com/adamghill/django-fbv)

## Commonly Used Apps

- [model_bakery](https://github.com/model-bakers/model_bakery)
- [factory-boy](https://github.com/FactoryBoy/factory_boy) `fetching fake data`
- [django-braces](https://github.com/brack3t/django-braces) `classed based view`
- [djang-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) `awesome`
- [django-guardian](https://github.com/django-guardian/django-guardian)
- [django-jimmypage](https://github.com/yourcelf/django-jimmypage) `caching`
- [cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django)
- [pytest](https://github.com/pytest-dev/pytest)
- [coveragepy](https://github.com/nedbat/coveragepy)

## Django Newsletter

- [Django News](https://django-news.com/)
- [Django Trending Packages](https://django.wtf/)
- [Django Books](https://djangobook.com/)
- [Discover latest content from the Django community](https://djangofeeds.com/) `videos/articles`
- [Django Packages](https://djangopackages.org/)

## Tutorials/Articles

- [Mastering Django Tutorials](https://masteringdjango.com/mastering-django-tutorials/)
- [Understanding Django](https://www.mattlayman.com/understand-django/)

## Django Podcasts

- [Django Riffs](https://djangoriffs.com/)
- [Django Chat](https://djangochat.com/)
