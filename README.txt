Using this repo to mark my django learning progress. Refollowing this demo for now https://docs.djangoproject.com/en/3.1/intro/tutorial01/

## Notes
----starting project and running server---
python -m django --version
django-admin startproject mysite
python manage.py runserver

---Creating an app---
Can be top level or submodule of the project we just created
I want to be able to import as top level so cd back and put in top level mysite
create app `python manage.py startapp polls`
add a view to the polls app
add a urls.py file to the poll app