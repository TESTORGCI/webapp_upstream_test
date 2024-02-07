webapp Prerequisites softwares and libraries MySQL DB NodeJS (Version 20.9) Sequelize (3rd party package for ORM in Node) bcryptjs express.

Steps to deploy it locally. 

Run npm install to install packages Once node_modules is installed. 

Create a .env file and the following. Make sure DATABASE, DATABASE_USER, DATABASE_PASSWORD is provided in the .env file.
 
PORT = 8080
DB_PORT = 3306
WEBSERVER_HOSTNAME = localhost
DATABASE_HOSTNAME = localhost
DATABASE = 
DATABASE_USER = 
DATABASE_PASSWORD = 
DIALECT = mysql

 
To run the application run npm start