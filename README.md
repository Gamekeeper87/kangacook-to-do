## Introduction

This is a simple To-do application built off Django and React following the instructions laid out in the interview email from Jeff Cheng of Kangacook and Roulettech. Axios is the API I used to create requests to the API endpoints on the backend server, allowing CRUD operations within Django's REST framework. It will be hosted using AWS S3 frontend and EC2 backend.

## Requirements
* Python3 (python.org/downloads)
* Pipenv (pip install pipenv OR pip3 install pipenv)
* Django (pip install django)
* Node.js (node.js installer)
* Bootstrap (npm install bootstrap)
* Reactstrap (npm install reactstrap)

## Getting started
1. Navigate into the directory ```[cd kangacook-to-do]```
2. Source the virtual environment ```[pip install pipenv]```
3. Install the dependencies ```[pip install django]```
4. Navigate into the frontend directory ```[cd frontend]```
5. Install the dependencies ```[npm install]```

## Run the application

You will need two terminals pointed to the frontend and backend directories to start the servers for this application.

1. Run this command to start the backend server in the backend directory: ```[python manage.py runserver]``` (You have to run this command while you are sourced into the virtual environment)
2. Run this command to start the frontend development server in the ```[frontend]``` directory: ```[npm start]``` (This will start the frontend on the adddress [localhost:3000](http://localhost:3000))

## Built With

* [React](https://reactjs.org) - A progressive JavaScript framework.
* [Python](https://www.python.org/) - A programming language that lets you work quickly and integrate systems more effectively.
* [Django](http://djangoproject.org/) - A high-level Python Web framework that encourages rapid development and clean, pragmatic design.
