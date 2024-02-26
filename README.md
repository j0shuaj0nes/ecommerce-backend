# ecommerce-backend
Back end for an e-commerce site by modifying starter code. Configured using a working Express.js API to use Sequelize to interact with a MySQL database.

## Description
This application runs the back end for an e-commerce website. It uses Sequelize to retrieve data from a MySQL database of categories of products, products and product tags. 
This project was created to help me build an understanding of the fundamental archecture of e-commerce sites. 

## Installation
Run 'npm i' in the integrated terminal to install necessary packages for this app. 

## Usage
The user opens the server.js file and then opens the integrated terminal. They then run 'mysql -u root -p' and login to their MySql. They then run ' source ./db/schema.sql' to connect to the database. Next they exit MySQL using the 'exit' command. Then the user can run the seeds in node using the command 'node run seeds'. They can then start the server using the command 'node server.js'. They can then use insomnia to find, create, update and delete categories, products and product tags. Refer to the [walk through video](https://drive.google.com/file/d/16joztDWnyHj5oRcJS4fCam8jwP-vlWjy/view)for a run through of how this app works.

## Credits
* [Insomnia](https://insomnia.rest/) <br>
* [MySQL2 package](https://www.npmjs.com/package/mysql2)
* [Express.js](https://expressjs.com)

## Walk through video link
Link to Video [Here](https://drive.google.com/file/d/16joztDWnyHj5oRcJS4fCam8jwP-vlWjy/view)
