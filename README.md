# E-commerce

## Description
Interact with the back-end database to view the E-commerce categories, products, tags and product tags. Using a program like Insomnia Core, you can test out the CRUD methods, create (POST), read (GET), update (PUT), and delete (DELETE) data within the databases. 

## Table of Contents 
* [Installation](#installation)
* [Usage](#usage)
* [Video](#video)
* [License](#license)

## Installation 
Clone the repository to a local directory. Type the following into the command line "npm init" then "npm i" to install relevant packages. You will need to create the database within mysql and to login you will type "mysql -u root -p", if not already created you will need to make a new database "CREATE DATABASE <database name>;" then "USE <database name>;" finally "source schema.sql;". This will create the database and you can type "quit;" to exit mysql command line. Once the packages are installed, update the .env file with your mysql password and then add the .env file to you .gitignore folder. This will protect your log in credentials. 

## Usage
To begin interacting with the ecommerce_db, you will go to the command line in the root directory of the repo, and type "node server.js" or "node server" and from there, open Insomnia Core to interact with GET, POST, PUT and DELETE.

## Video
https://drive.google.com/file/d/1oP44jtbRUzoh4FkgmKDJGbJ-9rnnZTGU/view


## License
Node.js, MySQL, Heroku, Insomnia Core

## Contributing
To contribute, view the open issues tab within the Github repo and following the listed directions if posted. 