# ryans-ecommerce-app

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description

Ecommerce is a massive market that's only getting bigger every year, and with that, an ever-incresasing number of business owners are eager to capitalize on this wave and set up an online presence of their own. One major hurdle in that is creating the back end to connect their front end architecture to a database of relevant product info. This app does just that! Via API requests, one can view, create, update, and delete products, tags and categories from the ecommerce_db database, all of which can be combined with a front end to make a fully functioning online store.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)
- [License](#license)

## Installation

Clone the repository, and within the repository directory, rename env.example to just .env, and within that file, insert your MySQL username and password. After that, unless you're running MySQL and Sequelize through MAMP, open config/connection.js and change the port number from 8889 to 3306. From there, use the terminal to cd into the repository directory, then ```run npm i``` to install the necessary packages, run ```mysql -u root -p``` then ```SOURCE db/schema.sql``` to create the ecomerce_db database, and finally ```npm run seed``` to seed the database.

## Usage

To use, either combine with fetch requests on the front end, or test the /api routes in insomnia, as displayed in this [demo video](https://drive.google.com/file/d/14fwdrFcCdsZXaJZkaVc0fCZqaPZI9SDM/view)

## Contributing

Please contact me via email for contribution requests.

## Tests

The routes can be tested in insomnia.

## Questions

Github: rdalby2002

Email: ryancdalby@gmail.com

For questions, email is my main point of contact
  
## License

This project is licensed under The MIT License.
  