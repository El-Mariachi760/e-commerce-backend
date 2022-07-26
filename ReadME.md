# E-Commerce Back End

## Description

An Application backend for an e-commerce website

## Technologies used 

-   Mysql2
-   Express
-   Sequelize
-   dotenv

## Demo

MySQL sourcing

https://user-images.githubusercontent.com/94568874/180625856-7eccc4ef-857f-412a-bf8b-f88adcd419d6.mp4

Routes demo

https://user-images.githubusercontent.com/94568874/180625418-ecc8751c-6d95-4db3-a4e0-f90437b57662.mp4


## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```


## Acceptence Criteria

```
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


## Installation
### In the command-line:

npm init

npm install mysql2

npm install sequelize

npm install dotenv

npm install express
