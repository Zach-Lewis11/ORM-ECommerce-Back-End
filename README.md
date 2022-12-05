  ![License](https://img.shields.io/badge/License-MIT-blueviolet.svg)

# ORM-ECommerce-Back-End

  ---

  ## Description

13 Object-Relational Mapping (ORM): E-Commerce Back End

This is an exercise to demonstrate how basic routes would work with a MySql database in a E-Commerce Site

---

## Table of Contents

* [Installation](#installation) 
* [Usage](#usage) 
* [License](#license) 
* [Contributing](#contributions)
* [Technology Used](#technology-used) 
* [Questions](#questions)

---

## Installation

TO try this application for yourself, clone the repo into your own work environment. Once you have done that you will need to set up the .env file so it looks like the following:
```
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PASSWORD='<Your password here>'
```
Once you have made the .env file, then you need to use the `npm i` in the terminal. After you have done that, open another terminal in the `db/schema.sql` file and type the command `mysql -u root -p` then enter your password, now type `source schema.sql` to create the database. 

Once the db has been created you can navigate back to the terminal opened at the server.js file and type the `npm run seed` command followed by the `npm start` command. once you have done that the server is up and running. 

---

## Usage

Now that the server is running and the db has been created and seeded. you will want to open up insomnia to try the different routes out. when insomnia, make sure you are making the calls to `http://localhost:3001/api/`. 

---

## License

[MIT](https://choosealicense.com/licenses/mit/)

---

## Contributions

If you have any thought on improvement or want to contribute, please email me at the address listed below 

---

## Technology Used

To create and test this application, I have used the following: 

* Express
* Mysql 2
* Sequelize
* Insomnia
* dotenv
* Node
* Nodemon
* NPM 
* VS Code
* Github

---

## Questions

If you have any questions, please contact me at ztak78@gmail.com or head over to my <a href="https://github.com/Zach-Lewis11" target="_blank">GitHub</a>

---
