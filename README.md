# School Management System

## Introduction

Web based School Management System are designed to manage and store project information that are used in web based applications. This package was developed to help the school to manage various details pertaining to its students. This project aims to create a student information system that manages student and staff details. The system is implemented using the Python programming language with SQLite as the database. The front-end of the system is created using HTML, CSS.

## Features of the project

* Student Management - Add student, updating student details, view profile
* Teacher Management - Add teacher, edit teacher details

## Technology used

We have developed this project using the following technology-
* HTML - Page layout has been designed in HTML
* CSS - Page layout has been made creative using CSS
* Python - All the business logic has been implemented in python
* SQLite - SQLite database has been used as database for the project

Front end: HTML, CSS
* HTML : HTML is used to create and save web document
* CSS : CSS is used to make website more appealing and attractive

Back end : SQLite, Python
* SQLite : SQLite is a database, widely used for accessing querying, updating, and managing data in database
* Python : Python is a very popular and trending programming language used in many IT sectors.

## Modules and description of the project

### Student Module:

The main purpose of this module is to provide all the functionality related to the students. It tracks all the information and details of the student. We have developed all type of Create, Read, Update, Delete operations of the students. This is a role based module where admin can perform each and every operation on data but the student will be able to view only his/her data, so access level restrictions has been implemented on the project.

* Features of student module

- Admin can add new students records
- Admin can edit, update, delete records of the student
- Student will be able to see and update his details.

### Attandance Module
  The main purpose for developing this module is to manage the attandance of the students datewise. So all the attandance will be marked by admin or faculty and student will be able to see only his/her attandance. Admin can see the list of all the attandance and filter it according to the students.

* Features of this module

- Admin can mark the student attandance
- admin can edit/delete the student attandance
- admin can see the list of all student attandance
- student can see his attandance

### Functionality performed by student user
 this are the functionality performed by the student users

- login for student
- change password
- edit profile
- view attandance history

### Functionality performed by the Admin User

This functionalities are performed by the Admin User

- Login for admin
- Edit profile for admin
- Access to all student and staff details

#### Manage Student
- Adding new student
- Edit existing student
- View profile of student
- Listing of all student

#### Manage Attandance
- Add attandance of student
- Edit attandance of student
- Listing of attandance
- Filter attandance according to student

### Python Explaination
- manage.py:
This file helps us to start the server that gives us the link to the start the website on the client side. We use Django for the server side.(https://github.com/shaun2015/School-Information-system/blob/main/manage.py)

- admin.py:
In this file we give the admin the privilages to register a student, teacher. We also give admin the privilages to access the attendence, and also the admin is able to display and write any notices that they want everyone to see.(https://github.com/shaun2015/School-Information-system/blob/main/student_management_app/admin.py)

- forms.py:
In this file we configure the forms for admin, students and teachers. We make forms to store the information about the student, teacher or admin who is registering or is login-in. We also use forms to generate username and password for the user. In this file we also configure the form for attendence which is whether the student is present or absent.(https://github.com/shaun2015/School-Information-system/blob/main/student_management_app/forms.py)

- models.py:
In this file we configure models for the students and teachers. We also create models for attendence page and also we create a model for the notice page.(https://github.com/shaun2015/School-Information-system/blob/main/student_management_app/models.py)

- views.py:
In this file we configure the pages and links with html templates. We link the fuctions with html pages for the users who have successfully logged in or throw an error if there was any error while login-in. This file also helps the fuctions that are used to sign-in/register to link with their respective html pages. This file also contains fuctions that help to authenticate the user and check if the username and password is right or wrong. So basically we use this file to link the html pages with thier respective fuctions and also this file checks the authentication process of the project.(https://github.com/shaun2015/School-Information-system/blob/main/student_management_app/views.py)


### Contribution Report

### Shaun Christopher Chaudhary (10622059@mydbs.ie)

##### Frontend
- Implemented the user login page using HTML and CSS
- Created the design for the dashboard using CSS and JavaScript
- Implemented the navigation bar for the admin and staff portals
- Implemented the CRUD operations pages for the admin portal using HTML and CSS

##### Backend
- Designed the database schema for the student information system
- Created the logic for displaying statistics on the admin dashboard
- Implemented the backend functionality for user authentication and authorization
- Created the logic for CRUD operations on the database


### Swikar Omargekar (10608904@mydbs.ie)

##### Frontend
- Created the design for the home page of the student portal using CSS and JavaScript
- Implemented the design for the staff portal dashboard using CSS and JavaScript
- Implemented the pages for student details, course details, and subject details using HTML and CSS
- Tested the frontend for usability and responsiveness

##### Backend
- Implemented the functionality for CRUD operations on student and staff details using Python and Django
- Implemented the logic for calculating and displaying information related to courses and subjects
- Set up the SQLite database using Python
- Tested the backend functionality using Django's testing framework

- ### References
- Halachev, P., 2020. Web application with Python and security of the information system. Security & Future, 4(3), pp.103-106.
- Prokofyeva, N. and Boltunova, V., 2017. Analysis and practical application of PHP frameworks in development of web information systems. Procedia Computer Science, 104, pp.51-56.
- https://www.w3schools.com/html/
- https://data-flair.training/blogs/python-school-students-management-system/
- https://itsourcecode.com/free-projects/python-projects/school-management-system-project-in-python-with-source-code/?utm_content=cmp-true
- https://github.com/akkupy/School-Management-System
- https://github.com/topics/school-management-system?l=python

