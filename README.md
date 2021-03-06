# Ticket Management System

Ticket management system front-end with Angularjs, HTML, Bootstrap. REST API to Django with PostgreSQL database.

## Problem Description:

We want to create a comprehensive system where user can submit their tickets for Support Team anonymously as well as after login.
Employee users can login with their cradentials, they can view the tickets, perform modifications on that tickets and remove it.
Additionally logged in users can add comments on the tickets and view comments of others.
There should be front-end and backend to communicate with database.

## Solution :

#Introduction :

Simple and efficient Ticket Management system, loaded with AngularJS, HTML, Bootstrap front-end and RESTful API to communicate with Django backend.

#Features : 

  - [x] Simple and userfiendly user interface.
  - [x] High performance front-end with AngularJS
  - [x] Secure RESTful API with Django
  - [x] PostgreSQL for database storage
  
#The solution provides following functionalities:

- Create Support Ticket as anonymously user
- Employee Login
- View the listing of tickets, Create, Update and delete ticket.
- Commnets can be added and also comments history is maintained in order.


##Technical Decisions :

#Front-end :

As HTML, Bootstrap and javascript is widely used and adopted, so I have used them with combination of AngularJS. Because AngularJS is a powerful javascript frameword
also it's opensource and provides developers facilities to write client side application in clean MVC manner.It can be easily handled by all browsers.

#Backend :

Here for backed, Django is used which is widely used frameword written in Python. It has simple and expressive syntax which provided ease to develop and mantain the application.
Django is also a open source framework, which accelerates the development of custom application and supports wide array of database.  


## How to run the code :

#Front-end :

It's very simple and easy, just put the folder in your server(Apache) and run your localhost followed by the slash and your application folder.
i.e. http://localhost/ticket_management

-You need to change the API Url which is located on the first line in two algularJs controllers to communicate with Django API
 -[PROJECT FOLDER]\scripts\angular\Controller\ticketController.js
 -[PROJECT FOLDER]\scripts\angular\Controller\userController.js

#Backend :
I have used python 2.7 and django 1.11.4. You will get all necessary library detail (requirments.txt) in backend also attach database file (ticketsystem.sql).Database is in Postgresql.
Steps to install backend in Ubuntu 

- 1.Install Python
- 2.pip install virtualenv
- 3.virtualenv env
- 4.cd env/bin
- 5.ktn@ktn:~/env/bin$ source activate
- 6.(env) ktn@ktn:~$ cd sentact
- 7.(env) ktn@ktn:~$ pip install -r requirements.txt
- 8.(env) ktn@ktn:~/sentact$ python manage.py runserver 192.168.1.119:8084
Output will be
- (env) ktn@ktn:~/sentact$ python manage.py runserver 192.168.1.119:8084
Performing system checks...

System check identified some issues:

WARNINGS:
?: (urls.W005) URL namespace 'v1' isn't unique. You may not be able to reverse all URLs in this namespace

System check identified 1 issue (0 silenced).
September 15, 2018 - 14:17:43
Django version 1.11.4, using settings 'sentact.settings'
Starting development server at http://192.168.1.119:8084/
Quit the server with CONTROL-C.

For stop devlopment environment 
ctrl + c
For run test case
 after 7th setp you can direct run this commands
- (env) ktn@ktn:~/sentact$ python manage.py test
Output will be
(env) ktn@ktn:~/sentact$ python manage.py test
Creating test database for alias 'default'...
System check identified some issues:

WARNINGS:
?: (urls.W005) URL namespace 'v1' isn't unique. You may not be able to reverse all URLs in this namespace

System check identified 1 issue (0 silenced).
.......
----------------------------------------------------------------------
Ran 7 tests in 0.269s

OK
Destroying test database for alias 'default'...



NB: As I have very good experience working with angularJs, Django and web-services, I choose to use those technologies. It took me around 16 hours to complete this including few unit test cases and this file as well.

I am open to quickly adopt new technologies as well.

