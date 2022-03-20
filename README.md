# ORM e-commerce Back End

## Description

- Purpose of this project: A back-end for an e-commerce site
- Problem(s) the app solves: A company not having a working back end for their site
- Languages used: HTML, JavaScript, SQL
- Brief description: A back end for an e-commerce website that uses the latest technologies so that the user's company can compete with other e-commerce companies

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)
- [Links](#links)

## Installation

This app requires the installation of mysql2, sequelize, express, and dotenv to function. All are included in the package.json file and can be installed with the following input:

```bash
npm install
```

## Usage

When the user adds their database name, MySQL username, and MySQL password to an environment variable file, they are able to connect to a database using Sequelize.
The schema can be entered by copying the contents of the schema.sql file, pasting it into MySQL Workbench, and executing the schema. This will generate the new database. After the development database is created, the user seeds the database with test data with the following input in an integrated terminal:

```bash
npm run seed
```

The server is started using the following input in an integrated terminal:

```bash
npm server start
```

If nodemon is installed, the user can also start the server using the following input in an integrated terminal:

```bash
nodemon start
```

Then the server is started and the Sequelize models are synced to the MySQL database. When the user opens API GET routes in Thunder Client for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON. When the user tests API POST, PUT, and DELETE routes in Thunder Client for categories, products, or tags, the user is able to successfully create, update, and delete data in the database.

## Credits

For this project, we were given starter code and instructed to build the back end. The back end coding was done by our instructor, Scott Brunswig. He walked through coding the homework over a series of office hours and, when it was complete, we all cloned the repository. I then created a new repository, copied the folders/files over, created my own env file, modified the connection.js file, and created the README.

- Scott's github: [sbrunswig](https://github.com/sbrunswig)

## Contributing

If you would like to contribute to this application, please follow Creative Contribution guidelines.

## Tests

You can test this application by checking the API routes using Thunder Client or Insomnia.

## Questions

If you have any questions:

- Email me: [meegan.r.anderson@gmail.com](mailto:meegan.r.anderson@gmail.com)
- Go to my github: [NotANewt](https://github.com/NotANewt)

## Links

- Here is Scott's repo: [sbrunswig/hw13](https://github.com/sbrunswig/hw13)
- Here is my repo: [NotANewt/ORM e-commerce Back End](https://www.github.com/NotANewt/hw13_orm_ecommerce_back_end)
- Here is part one of the video walkthrough: [Walkthrough Part 1: generate the database, seed the database, and start the application's server ](https://drive.google.com/file/d/1dtQgenWwFjI0MSwAzBL8WAIzg89AS8WG/view)
- Here is part two of the video walkthrough: [Walkthrough Part 2: GET routes to return all and get routes to return a single category, product, or tag ](https://drive.google.com/file/d/1z-9lhlGs7ZYIZ_1actbx4IrJJSun6MWI/view)
- Here is part three of the video walkthrough: [Walkthrough Part 3: POST, PUT, and DELETE routes for categories, products, and tags ](https://drive.google.com/file/d/1h3MFf8neFXhTzhdgywdMCRdqMkzJOBnk/view)
