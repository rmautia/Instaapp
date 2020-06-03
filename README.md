# INSTAGRAM CLONE
## Description

InstaClone is a social  web application that is used by users to post their pictures, follow other users and like other their pictures. They can also follow other users as in instagram app. link to the live site [here](http://mirrayinsta.herokuapp.com/) 
please note password should contain mixed characters and symbols. 


## Features
- Users create an account and confirm through email verification.
- User can log in to application and view other peoples posts.
- Users can follow other users and unfollow them.
- A user can like and comment on a post.
- A user can upload posts and edit their profile.
- Admin can regulate images uploaded by deleting from the admin dashboard as well as completely close a users account.



## Technologies Used
    - Python 3.8.2
    - Django MVC framework
    - Django-boostrap4
    - HTML, CSS 
    - Postgressql
    - Heroku
    - Uploadcare

### Prerequisite
The Instaclone project requires a prerequisite understanding of the following:
- Django Framework
- Python3.8
- Postgres
- Python virtualenv virtual

## demo login credentials
username: demo
password: Demopass1.

#### Clone the Repository
####  Activate virtual environment
Activate virtual environment using python3.6 as default handler
    `python3.8 -m venv --without-pip virtual && source virtual/bin/activate`
    `curl https://bootstrap.pypa.io/get-pip.py | python`
####  Install dependancies
Install dependancies that will create an environment for the app to run `pip install -r requirements.txt`   `pip freeze > requirements.txt`
####  Create the Database
    - psql
    - CREATE DATABASE instagramdt;
####  .env file
Create .env file and paste paste the following filling where appropriate:

    SECRET_KEY = '<Secret_key>'
    DBNAME = 'instagramdt'
    USER = '<Username>'
    PASSWORD = '<password>'
    DEBUG = True
#### Run initial Migration
    python3.8 manage.py makemigrations instagram
    python3.8 manage.py migrate
#### Run the app
    python3.8 manage.py runserver
    Open terminal on localhost:8000

## Bugs Within the application
There are no known bugs so far. If found, KIndly get in touch through my contact addresses listed below.

## Contributors
    - Raphael Nyangenya Mautia
    - Shoutout to all those whose code was referenced in any section of this application. 

### Contact Information
raphaelnyangenya@gmail.com | bookiedonate@gmail.com

#### Peace Info. 
we are faced with a very serious pandemic. please try as much as possible to stay home, stay safe, keep distance and remember to sanitize.😇 

