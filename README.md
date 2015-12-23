# django-sb-admin2-dark

## Screenshot
![](https://raw.githubusercontent.com/patriz/django-sb-admin2-dark/master/screenshot.png)

## Prerequisites

Install virtualenvwrapper for Python 3.4 on Ubuntu

	sudo apt-get install python3.4-venv

## Installation

Clone a repo

	git clone https://github.com/patriz/django-sb-admin2-dark.git && cd django-sb-admin2-dark

Create a virtualenv with virtualenvwrapper

	pyvenv-3.4 .venv

Activate the virtualenv

	source .venv/bin/activate

Install required modules

	pip install -r requirements.txt

Install bower's components (react-bootstrap, sb-admin2 and etc)

	./manage.py bower install

## Run

Run server

	./manage.py runserver
