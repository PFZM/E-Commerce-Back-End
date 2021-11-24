# README -  E-Commerce Back End


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Link to see the deployed application:

[YouTube video](https://youtu.be)

## Description

This is a Back end application for an e-commece site. The application is build with Node.Js and uses the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

## Table of contents:

1. [Installation](#installation)
2. [Usage](#usage)
3. [License](#license)
4. [Contributing](#contributing)
5. [Questions](#questions)

## Installation

1. Fork repository
2. Clone repository to local environment.
3. Node.js must be installed.
4. To install all the dependencies (dotenv, express, mysql2 and sequelize) use the following command:

```bash
npm install
```

5.Use the `.env` file to store sensitive data: MySQL username, password, and database name.

6. Loging into MySQL and use the `schema.sql` file in the `db` folder to create your data base with the following MySQL shell command:

```bash
source db/shema.sql;
```
7. Seed the database  with the following command:

```bash
npm run seed
```

## Usage

The application is invoked by using the following command (on the directory containing this project):

```bash
node server.js
```

```md
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


## License

This project is covered under the MIT license.

## Contributing

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.
Please note we have a code of conduct, please follow it in all your interactions with the project.
Contributions follow the [Contributor Convenant](http://contributor-covenant.org/version/1/4/).

## Questions

[GitHub profile](http://github.com/PFZM)

[Contact Me - Email](mailto:pfzm@hotmail.com)

