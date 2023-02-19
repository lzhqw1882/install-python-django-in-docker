# Install the Django in the Docker

This is the set environment for Django in the Docker.

## Contents

* [Installation for local environment](#Installation for local environment)
* [Installation for Docker](#Installation for Docker)


## Installation for local environment

1. You will prepare install python in your local environment.


01 step : Install Django in your local:

    $ pip install django 

02 step : Make project in your local

    $ python-admin startproject src .

03 step : Execute Django run server

    $ python manage.py runserver

04 step : Open your browser and connect (http://localhost:8000)

05 step : Make dependency file "requirements.txt"

    $ pip freeze > requirements.txt


## Installation for Docker

1. You will prepare install docker in your local environment.

01 step : Make Docker image file.

    $ docker build -t install-python-fastapi-in-docker . 

02 step : Execute docker-compose file.

    $ docker-compose up -d

And open the browser and connect (http://localhost:8001)