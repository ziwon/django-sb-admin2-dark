# django-sb-admin2-dark

## Demo
![](https://raw.githubusercontent.com/patriz/django-sb-admin2-dark/master/screenshot.png) 

## Installation

Install virtualenvwrapper for Python 3.4 on Ubuntu

	sudo apt-get install python3.4-venv

Create a virtualenv with virtualenvwrapper

	pyvenv-3.4 .venv

Activate the virtualenv

	source .venv/bin/activate

Install required modules

	pip install -r requirements.txt

Install bower's components (reactive-bootstrap, sb-admin2 and etc)
	
	./manage.py bower install

## Running

Run server

	./manage.py runserver


