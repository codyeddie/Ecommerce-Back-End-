# Ecommerce Back-End

## Description 
The point of this application is to view, add, update and delete categories/products/tags in the ecommerce database.

* Heroku Link
https://ecommerce-back-end-08102022.herokuapp.com/

## Table of Contents

* [Installation](#installation)
* [Contribution](#contribution)
* [Video Demo](#video-demo)

## Installation 
To install this application you must first clone the repo to your local machine. Once the repo is cloned to your machine, you must then install the dependencies in your root directy after an NPM install. Once mysql2 and inquirer have been installed you must create a .env file and input the DB_NAME, DB_USER, and DB_PASSWORD fields to match what's in the connection.js file. You will also have to put your mysql password into the password value in the connection.js file. Once that is done you can login to the mysql shell and source the schema.sql files in the db/ folder. Once that files have been sourced using the 'source db/schema.sql' command then your next step is to seed the database using 'npm run seed' in the command line. The last step is to run 'npm start' command in your command line. From here, you should be able to launch insomnia and use the routes as needed. 

## Contribution 
I utilized my tutor and referenced previous module work and lessons to complete this assignment. 

## Video-Demo
* Part One
https://drive.google.com/file/d/1THCUlbNfiFITBtpXSZCTc_c4gCL2hntE/view
* Part Two
https://drive.google.com/file/d/1WL6sqFLKGvXwl4btMtju_VgcwVms_6hv/view

![Screenshot](/assets/imgs/screenshot.png)
