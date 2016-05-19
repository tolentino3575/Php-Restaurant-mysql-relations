#Hair Salon Code Review
PHP week 3 code review: Database Basics

##Author

This project was created by Erik Tolentino

##Description

This app will allow user to create restaurants and cuisines. Using relation statements, a cuisine can belong to many restaurants, but a restaurant can't belong to many cuisines.
Users have the ability to also update or delete a restaurant or cuisine, as well as add. 

#Setup

To View:
* Git clone this repository

* From terminal, enter "mysql.server start" to start the MySQL servers and enter mysql shell
* Next enter "mysql -uroot -proot" to set username and password for PhpMyAdmin

* From bash terminal, enter "apachectl start" to start PhpMyAdmin
* In browser, type "localhost:8080/phpmyadmin"
* If prompted, both your username and password are "root"

* From PhpMyAdmin, import "cuisine" databases included in folder

* From mysql shell in terminal, enter "USE cuisine" to enter database

* From bash terminal, run "composer install" while in project root folder

* From bash terminal, enter "php -S localhost:8000" while in the web folder

* To view, type "localhost:8000" in browser

#Technologies Used:

* Php
* PhpMyAdmin
* Apache
* MySQL
* PHPUnit
* Silex
* Twig
* Atom
* Terminal
* GitHub
* Bootstrap
* HTML

#Legal

* MIT Licensed
* Copyright (c) 2016 Erik Tolentino
