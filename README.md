# **Thai History**

This project is a Unity Game App, about Thai history.

It contains 2 main parts :
- Unity client
- Back-end server (web server built with PHP)

This project is intended to demonstrate how you can communicate between any server and unity using RESTapi technology.

## How to run server:

You need to have php installed in your machine. (please visit [PHP official website](http://www.php.net/))

The other requirement is you need a database server. (preferrably [MySql](https://dev.mysql.com/downloads/mysql/) Server)

You can install [xampp](https://www.apachefriends.org/index.html) instead which is a framework that contains all the mandatory requirements to run this project.

Without actually deploying the web server, you can use command line to run the back-end by using PHP library called 'artisan'. (included with the project already)

1. open cmd (commandline) in the back-end project's root folder. (The root folder is the parent folder of the 'app' folder)
2. then, run this command : 
```php
php artisan serve
```

## The Unity project:

There is a .scene file called "Home", you can start with that to explore this app.

**_This project need user account to log in_**

you can register your account by running the server then go to browser and open the webpage : localhost:8000 (this is default url, you should see the actual url when you run the command to start the server)

# **Status**

Still in progress

- can login
- can register
- can show history timeline
