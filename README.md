# TODO API

To run TODO API on local machine you need to do the following steps:

* First of all, clone or download TODO API project sources (<https://github.com/konstantinstukov/ToDoApi.git>);

* After that, open console and change your work directory to your TODO API project folder;

* Next, you have to install pipenv for Python 3.7;

* Install pipenv locked packages: `pipenv sync -d`;

* Then connect to the virtual env: `pipenv shell`;

* Then run: `python manage.py runserver`;

* Now you can use API using `http://127.0.0.1:8000/api` url;
