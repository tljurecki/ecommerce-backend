# E-commerce Back End

This is a database and application back end for an e-commerce website.  This was built using MYSQL, Sequelize, Express.js, dotenv.

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Languages Used
* Express.js
* MYSQL2
* Sequelize
* dotenv

## Installation
To use this application you will need to install the following dependencies:
* Express.js
* MYSQL2
* Sequelize
* dotenv 

## Usage
After installing the dependencies, run the following prompts from the command line in your terminal
* mysql -u root -p
enter your passowrd when prompted
* source db/schema.sql
* quit
* npm run seed
* npm start
 Once the server is running, you will need to go to Insomnia to test out the api routes
 
 ## Screenshot
 
 <img width="1330" alt="Screen Shot 2022-05-23 at 9 04 58 AM" src="https://user-images.githubusercontent.com/99137308/169826076-27c022cc-6e12-4ca3-b5e3-61d9cfa7e68d.png">
<img width="1728" alt="Screen Shot 2022-05-23 at 9 56 16 AM" src="https://user-images.githubusercontent.com/99137308/169836051-a01e91c2-d8e5-4c1b-be33-971a2f7b7fa2.png">

<img width="1728" alt="Screen Shot 2022-05-23 at 9 55 51 AM" src="https://user-images.githubusercontent.com/99137308/169836069-4cec2bbf-67c3-4f97-927f-0c29dbaf9a15.png">

<img width="1728" alt="Screen Shot 2022-05-23 at 9 56 31 AM" src="https://user-images.githubusercontent.com/99137308/169836099-1d4c2b22-ac81-4ac3-93c7-e8d818dc9b14.png">

 ## Video Tutorial 
 Click the link to learn how to use this application https://drive.google.com/file/d/1Uh7BuK8AKd_wFmXnUw27lG_brwXVMKRL/view
 
 ## Repository 
 GitHub repo link [
](https://github.com/tljurecki/ecommerce-backend.git)
