# Project Documentation - User Auth System
# Module: User Auth System

## tech stack
* laravel > project development
* Mysql > database 

## Description: This project provides functionalities for user registration, login, and role-based access control.

## User Registration:

* Users can register with their name, email, password (Admin or User) through a web form.
* Form validation ensures:
* All required fields (name, email, password) are filled.
* Email addresses are unique and follow a valid format.
* After successful registration, users are redirected to the login page.

## User Login:
* Registered users can log in using their email and password.
* Authentication verifies user credentials against stored data.
* Only registered users with valid credentials can access the system.
* Upon successful login, users are redirected to a role-specific dashboard.


## Dashboard:

* Logged-in users see a simple dashboard page.
* The dashboard displays a welcome message with the user's name 




### Steps to run
clone project
copy .envexample and create .env file

run the project using php artisan serve , npm run dev