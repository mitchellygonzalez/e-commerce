# e-commerce

#### Github link:  https://github.com/mitchellygonzalez/e-commerce

## Table of Contents
* [Description](#description)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Installation](#installation)
* [Usage](#usage)
* [Contributors](#contributors)
* [Technology Used](#technology-used)
* [Questions](#questions)
 
## Description
This e-commerce app serves to allow users to write notes and save them. 

Here is the link to the video: 
screencastify link: https://watch.screencastify.com/v/vzArJxGrHvwnLY7RrSv3

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

## Installation
1. Clone this code onto a local repository.
2. Install Node.js, express.js, SqeMySQL2 (instructions below)
3. Download Insomnia

## Usage
1. Install Node.js by running the following on your terminal: npm init -y
2. Install dependencies such as Express, Sequelize, and MySQL2 by running the following on your terminal: npm install express sequelize mysql2
3. To get MySQL started, run the following on your terminal and enter your login credentials: mysql -u root -p
4. Create an "env" file in the root of the project, and in it enter the following inside the quotation marks. Remember to add this "env" file into your .gitignore file so that your credentials do not get uploaded onto a public network. 
DB_NAME = ecommerce_db
DB_USER = 'root'
DB_PW = 'your MySQL password'
5. Before heading onto Insomnia, run one the following in your terminal to start the project: node server.js OR npm start
6. Download Insomnia and create the Category, Product, and Tag folders and enter their corresponding http requests. Use the video in the description of this README.md as guidance for this step.

## Contributors
To contribute, you may clone this repo, and create a new branch to add your code. 

## Technology Used
- Node.js
- Express.js
- Sequelize
- MySQL
- MySQL2
- JS
- JSON
- Insomnia

## Questions
Any questions, contact me via email: abc123@gmail.com

