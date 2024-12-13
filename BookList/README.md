
## Create a Booklist project using plain Django, including those to:
- add new books
- list available books
- search for a specific book. 

## Scenario
- The manager should be able to add books on both the app and the website.
- Both the manager and visitors should be able to browse the available selection of books and search for a specific book.


## Implement


Setting  Virtual Environment
pipenv shell

Run this command to install the dependencies using the updated Pipfile: 
pipenv install (pipenv install django)

Create a project
django-admin startproject BookList .

create a Django app
python3 manage.py startapp BookListAPI

~Changes~
Commands To Perform Migrations
python3 manage.py makemigrations # To compile the migrations
python3 manage.py migrate  # To migrate the changes in Database



start the server to test if the installation was successful
python3 manage.py runserver

Using the command createsuperuser.
