# E-commerce-Back-End
## Description
This is a mysql database and application back-end for e-comerce site. Built with MySYQL2, Ecxpress, Sequilize and dotenv. The application is designed to be easily customizable and scalable, with the ability to add new features and functionality as needed. It also includes comprehensive documentation for developers to quickly understand how the application works and how to use it in their own projects.
User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
## Mock Up
The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:
![get-all-demo](https://github.com/JLoya900/E-commerce-Back-End/assets/118794860/f64f6b79-47ce-4396-8fb0-1b120adb013e)
The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:
![get-single-demo](https://github.com/JLoya900/E-commerce-Back-End/assets/118794860/7f3c6f6f-b84f-48cd-a758-40486aa4b8c3)
The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:
![categories-put-post-delete-demo](https://github.com/JLoya900/E-commerce-Back-End/assets/118794860/36f73bc1-d1a1-44a2-ba15-1581423dda1d)
##Installation
```
npm i

npm run seed

npm start
```
