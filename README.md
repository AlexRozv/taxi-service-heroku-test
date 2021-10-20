## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
Taxi service is a pet project that was created with the aim to show my skills in Java, OOP and SOLID principles, JDBC, Web.
This web application supports registration and authentication of a driver. You're able to add new manufacturers and cars to the database.
Other then key CRUD operations there are other features like adding driver to a car and showing a list of cars for currently logged in driver.

	
## Technologies
Project is created with:
```
* Java 11
* MySQL
* Javax servlet API
* Jstl
* Tomcat 9.0.50 (to run app locally)
```

## Setup
To run this project:

```
* install MySQL
* install Tomcat 9.0.50
* fork this project and clone it
* initialize your database using init_db.sql file located in recources
* add your info to ConnectionUtil located in util to be able to connect to your database
* run this project using Tomcat's local server
```
