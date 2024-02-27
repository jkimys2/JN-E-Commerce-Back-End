# JN-E-Commerce-Back-End


## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Links](#links)


## Description

Internet retail, also known as **e-commerce**, plays a significant role within the electronics industry, as it empowers businesses and consumers alike to conveniently engage in online buying and selling of electronic products. This project demonstrates the back end application for an e-commerce site. It incorporates a MySQL database along with model files built with Sequelize in order to create tables to hold data for an electronic based store. This application was completed by following the acceptance criterias listed below:

```md
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
```

Starter code was provided for this challenge, and the rest the application was completed with Express.js, Sequelize, and MySQL2. It was created in order to help businesses keep up with the demand of online shopping and helping them keep a better log on all of their products that they provide for their consumers. By running the code ```node server.js```, the user is connected to the server, and they are able to test all of the different routes in Insomnia!


## Installation

In order to navigate through this e-commerce back-end application, you will need the following:

- Visual Studio Code <br>
- Node.js <br>
- Insomnia <br>
- And you will need to install the dependencies in the package.json file!


## Usage

Once you have the file in VS Code, you will need to install all of the dependencies by running ```npm install``` in the integrated terminal.

Once the dependencies are installed, you will need to create the database by going into the MySQL shell and running the schema file in the DB directory.

Then you will need to seed the database by running the code ```npm run seed``` into the integrated terminal.

Once you seed the database, you will need to run the server by typing ```npm start``` into the terminal. You will get a message in the terminal stating that your app is listening at the port 3001. Now you are able to test all of the routes in Insomnia.

In Insomnia, you can test each of the ```CATEGORY```, ```PRODUCT```, and ```TAG``` routes by passing in the different endpoints. The routes should return data provided that the endpoints were passed correctly!


## Credits

Thank you Chris B. for all your help! 😊👍


## Links

[GitHub Repository](https://github.com/jkimys2/JN-E-Commerce-Back-End) <br>
[Walkthrough Video]()