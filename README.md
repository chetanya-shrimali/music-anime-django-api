# music-anime-django-api
An application which uses Django `Rest-Framework` to create API's. \
It provides mainly two API's
  - Animes
  - Songs
 Each of them have a url to access them.
 
### requirements
support of `python 2.7+` \
install django 
  - `pip install django` 

install django `rest-framework` 
  - `pip install djangorestframework`
  
### how to run
- Get the requirements

`$ sudo apt-get install python-pip`

- Now run the server 
 	
	`$ python manage.py runserver`

open [127.0.0.1:8000](127.0.0.1:8000) in the browser


- Apply the migrations

	`python manage.py makemigrations`

	`python manage.py migrate`

- Create the admin

	`python manage.py createsuperuser`

- Add the relevant information

- open [127.0.0.1:8000/admin](127.0.0.1:8000/admin)

 
