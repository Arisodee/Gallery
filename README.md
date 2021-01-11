# Gallery

#### Author: [Ariso Okanga](https://github.com/Arisodee)

## Description
This is a web application that allows users to view some beautiful collection of pictures. They can also copy the link to a picture for use elsewhere.

## Features
- User can view images 
- User can see all images per location they were taken
- User can also search for images based categories
- Admin can upload images from the django dashboard

* Link to Live Site [The Gallery](https://ariso-gallery.herokuapp.com/)


## Technologies Used
    - Python 3.6
    - Django MVC framework
    - HTML, CSS and Bootstrap
    - JavaScript
    - Postgressql
    - Heroku

### Prerequisite
This project requires a prerequisite understanding of the following:
- Django Framework
- Python3.6
- Postgres
- Python virtualenv

## Setup and installation

#### Clone the Repo
####  Activate virtual environment
Create and activate virtual environment using python3.6 as default handler
    `python3.6 -m venv virtual && source virtual/bin/activate`
####  Install dependancies
Install dependancies that will create an environment for the app to run `pip3 install -r requirements.txt`
####  Create the Database
    - psql
    - CREATE DATABASE mygallery;
####  .env file
Create .env file and copy paste the following and fill in appropriately:

    SECRET_KEY = '<Secret_key>'
    DBNAME = 'gallery'
    USER = '<Username>'
    PASSWORD = '<password>'
    DEBUG = True
#### Run initial Migration
    python3.6 manage.py makemigrations gallery
    python3.6 manage.py migrate
#### Run the app
    python3.6 manage.py runserver
    Open terminal on localhost:8000

## Known bugs
No known bugs so far

## Support and contact details
 Incase you come across errors, have any questions, ideas ,concerns, or want to contribute to the application, feel free to reach me at : arisodee@gmail.com

### License

* LICENSED UNDER  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](license/MIT)