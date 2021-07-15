# E-Commerce Back End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/) [![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)](https://expressjs.com/)

This application provides the back end so that an e-commerce website and company can easily manage their products and have the technology to compete with other companies. It uses an Express.js API and the Sequelize package to interact with a MySQL database. 

It allows users to create and seed a database and to use API routes to update that database. For categories, products, or tags in the database, use API GET, POST, PUT, or DELETE routes to display, create, update, or delete data in the database.
    
## Table of Contents
 - [Installation](#installation)
 - [Usage](#usage)
 - [License](#license)
 - [Credits](#credits)
 - [Questions](#questions)
    
    
## Installation

The server is started through the command-line, and then the application can be tested using something similar to Insomnia Core. 

To use this application, clone and download the files from this repository. Run 'npm install' to install the packages included in the package.json (required packages are MySQL2, Sequelize, dotenv, and Express.js).

The schema.sql file can be used to create a MySQL database. A .env file must be created that includes the username, password, and new database name. Run 'npm run seed' in the command-line to populate the database tables (from the seeds.js files). The server can then be started in the command-line by running 'npm start'. 
    
## Usage

Once everything is downloaded, installed, and created (and the server is running), test the routes using Insomnia Core (or something similar). 

Run API GET routes for categories, products, or tags to see data from the database displayed as formatted JSON. (Find the syntax for the routes in the respective routes.js files: i.e., GET all tags would be 'http://localhost:3001/api/tags/').
Test API POST, PUT, and DELETE routes for categories, products, or tags in Insomnia Core to create, update, or delete data in the database. 

*See a video of the application in use [here](https://www.awesomescreenshot.com/video/4499834?key=e6b97f1ebf7ef168da3c5341bb964790).*

[![Walkthrough Video of Application](assets/ECommerce.gif)](https://www.awesomescreenshot.com/video/4499834?key=e6b97f1ebf7ef168da3c5341bb964790)
*(Click on GIF to be taken to the full video of the walkthrough.)*

*Use Insomnia Core to test different API routes*
![Screenshot of Insomnia Testing](assets/insomnia.png)

## License

This project is licensed under [MIT License](https://opensource.org/licenses/MIT).

## Credits

Starter front-end code provided by the University of Minnesota Coding Bootcamp.

## Questions

See more of my work on my [GitHub Profile](https://github.com/msteblu/).
For any additional questions, reach me at my email: megan@steblay.net.