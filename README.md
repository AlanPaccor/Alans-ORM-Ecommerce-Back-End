# Alan's Object Relational Mapping ORM E-Commerce Back End.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
## Description
The back-end database has been purposed towards e-commerce websites using Express.js API and Sequelize to connect to the MySQL database. The back-end database allows users to create a development database, seed it with test data, and sync Sequelize models to MySQL database. Users have the ability to use GET, POST, PUT, and DELETE routes to display and manipulate data in the users' database. Give it a try and see how it helps your company power up to the next level!


## The Challenge:
This challenge requires the creation of an e-commerce back-end site that meets specific user requirements. These requirements include the ability to connect to a MySQL database using Sequelize, create a development database that is seeded with test data, sync Sequelize models to the MySQL database, and display data from categories, products, and tags in a formatted JSON. The application should also be able to create, update, and delete data in the database.
## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

#Acceptance Criteria

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


GIF:
Figure .1 GIF
The following animation demonstrates the application functionality:
A user clicks on slots on the color-coded calendar and edits the events.

Usage Instructions
Repository: Open documentation run 'npm i' and update '.env'.
Create database: use the schema.sql file in the db folder with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.
Run 'npm run seed' to seed the database with test data. Then, run 'npm start' or 'nodemon' to start the server and sync the Sequelize models to the MySQL database.
Generate a development database with test data, use the schema and seed commands.
Use Insomnia to test http://localhost:3001 with the following route end points API GET, POST, PUT, and DELETE routes for categories, products, and tags, ensuring successful creation, updating, and deletion of data in the database.

Installation Process
Clone the Repository from GitHub (or) Download Zip Folder from Repository from GitHub.
Open the cloned (or downloaded) repository in any source code editor.
Open the integrated terminal of the document and complete the respective installation guides provided in "Built With" to ensure the cloned documentation will operate.
JSON: JSON
Dynamic JavaScript
Dotenv: 8.6.0
Express: 4.17.1
Node.js: Version 16.18.1
Express.js:Express.js
Node MySql2: 2.3.3
Sequelize: 6.29.3
Insomnia: by Kong
Nodemon: 2.0.12
Visual Studio Code: Website
What I Learned:
How to use Express.js to create a functional back end for an e-commerce website.
How to connect to a MySQL database using Sequelize and update environment variable files accordingly.
How to generate a development database with test data using schema and seed commands.
Continued Development:
Implement the latest technologies, such as Express.js, MySQL, and Sequelize to create a functional back end for the e-commerce website.
Ensure that the environment variable file is updated with the database name, MySQL username, and MySQL password to connect to the database using Sequelize.
Create schema and seed commands to generate a development database with test data, allowing for a smooth testing process.
License & Copyright ©
License: MIT Open Source Initiative Link

Copyright © 2023 Alan Paccor
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "
