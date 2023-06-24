# <h1 align="center">E-commerce-Back-End </h1>
Week-13 Challenge (Object-Relational-Mapping)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

*  [Description](#Description)
          <a name=“Description”></a>

*  [Screenshots](#Screenshots)
          <a name="Screenshots"></a>
   
*  [Technologies-Used](#Technologies-Used)
          <a name="Technologies Used"></a> 
          
*  [Installation](#Installation)
          <a name="Installation"></a> 
          
*  [Features](#Features)
          <a name="Features"></a>               
    
*  [Usage-Information](#Usage-Information)
          <a name="Usage Information"></a>  
          
*  [License](#License)
          <a name="License"></a> 
         
*  [Questions](#Questions)
          <a name="Questions"></a> 
          

##  Description 

This application provides an integrated MySQL database and Sequelize for the efficient management of e-commerce businesses. Sequelize serves as an ORM, enhancing code readability and reusability. Users can interact with the database through API routes, eliminating the need for a user interface. Overcoming challenges with table joins, the application simplifies complex relationships between categories, products, and tags. Future plans include implementing unit testing for reliability and expanding the database to encompass other business aspects. By continuously improving and adapting, this application empowers e-commerce businesses to streamline operations, enhance user experiences, and stay competitive in the evolving industry.

 
##  Live Screen Recording of Application Functionality 

https://drive.google.com/file/d/1_X3RTV-uSrPoPYFlvuF2TvFFi-ZD1I2C/view

## Screenshots 


## Technologies Used

This application is powered by Node.js (v16.19.1), Express.js (v14.17.1), JavaScript, MySQL, and Sequelize (ORM). It utilizes the node package manager (npm) dependencies sequelize (v5.22.5), mysql2 (v2.3.3), express (v4.17.1), dotenv (v8.6.0), and nodemon (v2.0.3). Also, the Insomnia application was utilized to test the functionality of routes within the program.

## Installation

1. Clone the repo: git clone git@github.com:Slfdspln/E-Commerce-Back-End.git

2. Open in VS Code. If you do not have VS code, you must install it.

3. Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however, this may vary, and the documentation should be consulted.

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install dependencies directly from the command line).

Commands to install each dependency:

* Command for sequelize will be npm i sequelize
* Command for mysql2 will be npm i mysql2
* Command for express will be npm i express@4.17.1
* Command for dotenv will be npm i dotenv
* Command for nodemon will be npm i nodemon

6. Next, you will need to make sure you have an added .env file within the root directory of your repository, within which you will pass your environmental variables specifying the database name, your MySQL username, and your MySQL password. This will need to be completed before running the application, and will allow the connection.js file to utilize your environmental variables keeping your sensitive information protected.

7. If you do not have a MySQL account, you will need to create one (see https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/).

8. Once all dependencies are installed, you will need to create the database. To do this you will need to navigate to the directory db directory containing the schema.sql file. Once there, you will need to open up a MySQL shell using the command mysql -u root -p, where you will then be prompted to enter you password. Once your password is entered you will be in the MySQL shell.

9. Once in the MySQL shell you will then run the command source schema.sql. This will create the database.

10. Once the database has been created, you will then need to seed the database (this will also create the model structure for the tables within the database). To do this, navigate to the root directory and run the command npm run seed. This needs to be done from the root directory because the .env file lives within the root.

11. Once the database has been seeded, you will then be able to run the command npm start from the root directory to spin up the server.

12. From there, you can utilize applications such as Insomnia to test the functionality of the routes within the program.


## Features

Features of this application include the users ability to manage the backend of their company's e-commerce website through Express routing. The functionality built within the application allows for users to navigate their company's database with GET routes, add and update new catagories, products, and tags to their website with POST and PUT routes, and delete any catagories, products, and tags no longer in use or that may be currently out of stock with DELETE routes.


## Usage Information

Usage of this application as of now, can be seen through the running and testing of routes with applications like Insomnia or strictly through using a MySQL shell. Once the database has been created, seeded, and the server spun up (see installation section for instructions on how to get the database set up and the server running), users can interact with the database through routing of different api end points.

## License

NOTICE: This application is covered under the MIT License

## Questions

Need more information? You can contact me through my LinkedIn or Email. Links provided below.

Click for LinkedIn -> [LinkedIn](https://www.linkedin.com/in/cristal-rivera-662b58248/)

Click to Email -> [Email](mailto:inaliaashanti@gmail.com?subject=[Email]%20Source%20Han%20Sans)

