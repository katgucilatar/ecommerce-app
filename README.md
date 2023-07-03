E-Commerce App
    
## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Tests](#tests)
* [Usage](#usage)
* [Contributing](#contributing)
* [Questions](#questions)

## Description
This E-Commerce app was created for an assignment by UNC Coding Bootcamp. This app utilizes Express.JS, MySQL, and Sequelize to create a database in which its data can be created, updated, and deleted.

Watch the following walkthrough video to see how this app works: 
https://watch.screencastify.com/v/xL97owiRmhvxZUXjydDe

## Installation
In order to download this code from the repository, one must have a software such as VS Code or one that's similar. Along with VS Code, it is necessary to download Node.JS and MySQL.

After downloading Node.JS and MySQL, it is important to install the packages associated with this app in order to be able to access its full properties.

Before opening this app in VS Code, make sure to Git Clone this project otherwise all packages will have to be installed manually.

Begin by opening the terminal, and typing in "npm init -y" as this will set a basic package.json file. 

We will now log into MySQL using "mysql -u root -p" and using "root" as the password. Once logged in, we're gonna source the schema by running "source db/schema.sql;" in the terminal. Once that's done, run "quit" in the terminal to exit MySQL.

Now that our schema has been sourced, we can seed the database. Simply run "npm run seed" in the terminal and it will seed the database.

Once all that has been done, now we can install everything by typing "npm install" and it will install the packages that have been installed into this app.

Lastly before we test this app, we can run "node server.js" or "npm start" in the terminal to connect to the server.

## Tests
Upon installing everything, this app is tested using Insomnia. There are categories, products, and tags and for each of those are a GET request obtaining all data information from each of those sections, a GET request obtaining single data information using its ID, a POST request to create an item to the database, a PUT request to update any information on the database, and a DELETE request to delete an item on the database. 

For this specific test, we are going to be creating an item, updating the name of that item, and deleting that item. 

Watch this in the following walkthrough video here:
https://watch.screencastify.com/v/xL97owiRmhvxZUXjydDe


## Usage
This app may be especially useful for those who own a business and would like some organization for their items. This app can also be used by someone who would like to open a business and would like to create a database and keep track of their products before store opening. 

## Contributing
Katrina Gucilatar with guidelines assigned by UNC Coding Bootcamp

## Questions
Contact me at the following for any questions: 
GitHub: https://github.com/katgucilatar  
Email: katgucilatar@outlook.com