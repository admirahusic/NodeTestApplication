# NodeTestApplication

In order to run application install needed dependencies:

npm install -g sails

npm install

# Seting up DataBase

Open  config/datastores.js

Create database datadb and testdb on your mysql server, and change database connection parameters

In order to do the integration testing import data provided in /database/testing.sql file.

# Run app

sails lift

# Run tests 

npm test
