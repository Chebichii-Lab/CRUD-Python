# TASK LIST

## Author
Natasha Serem

### Description
This a is a asimple CRUD example using Django. CRUD meaning Create, Read, Update and Delete.
In this example, a user can create a task, read the tasks created, update the task and delete and task.

### Setup and Instalations
To get the code, clone the repository:

$ cd CRUD-Python
$ pip install -r requirements.txt

### Installing and Activating Virtual Environment
$ python3.8 -m venv virtual
$ source virtual/bin/activate

### Create Database
$ psql
$ CREATE DATABASE (name_of_databse);

### Make Migrations
$ python3.8 manage.py check
$ python3.8 manage.py makemigrations (app_name)
$ python3.8 manage.py migrate 

###Testing the Application
$ python3.8 manage.py test (app_name)

### Running the appplication
$python3.8 manage.py runserver

Then once you are done, open your browser with the local host; 127.0.0.1:8000


