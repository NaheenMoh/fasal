This Project is based on Java Swings and MySQL, with the use of OMDB API.
this includes 8 classes, the program begins from splash.java class, 
it then goes into Login.java, if the user is new we have a signup option which is handeld by SignUp.java class
after login, the user is prompted to Project.java class the user can search a movie, the results are displayed, 
the user also has an option to add it to his MovieList.

total classes
(1) Splash
(2) Conn    #establishes connection with database
(3) Login
(4) SignUp
(5) Project
(6) API  #retrieves data from OMDB
(7) Display
(8) Movies


Database Tables

(1) UserDetails ( id,name,username,password)
(2) Movies (id,title,year)

Queries used
(1) create database fasal
(2) use fasal
(3) create table UserDetails (id int NOT NULL,name varchar(35) NOT NULL,username varchar(35) NOT NULL,password varchar(35) NOT NULL)
(4) create table Movies(id int,title varchar(35),year varchar(4))

Use java jdbc Driver to establish connection to application
