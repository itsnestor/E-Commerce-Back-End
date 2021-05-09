# E-Commerce-Back-End

[![mitLicense](https://img.shields.io/badge/license-MIT-green?style=plastic)](https://choosealicense.com/licenses/bsd-3-clause/)

## Description

  Built the back end for an e-commerce site by modifying starter code. Configured a working Express.js API to use Sequelize to interact with a MySql database.

  ```md
  AS A manager at an internet retail company
  I WANT a back end for my e-commerce website that uses the latest technologies
  SO THAT my company can compete with other e-commerce companies
  ```

## Table of Contents

  * [Installation](#installation)
  * [Usage](#usage)
  * [Links](#links)
  * [License](#license)
  * [Questions](#questions)

## Installation

  Make sure to have node.js installed before running application: https://nodejs.org/en/download/package-manager/

  Install the package.json by

  ```
  npm install
  ```

## Usage

  The application starts by running the command:

  ```
  npm run start
  ```

  ```
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

  Gif of testing GET routes for all categories, products, and tags:

  ![get routes all](Assets/GET-routes-to-return-all-categories,-products,-and-tags-being-tested.gif)

  Gif of testing GET routes by ID:

  ![get routes by id](Assets/testing-get-by-id.gif)

  Gif of testing DELETE, CREATE, and UPDATE category:

  ![post, put, delete category](Assets/testing-post-put-and-delete.gif)

  Gif of testing DELETE, CREATE, and UPDATE for products and tags:

  ![post, put, delete products and tags](Assets/post-put-delete-products-and-tags.gif)

## Links

  * Github Repository URL: https://github.com/itsnestor/E-Commerce-Back-End
  * Tested GET routes returning all categories, all products, and all tags: https://drive.google.com/file/d/1nSMdHJqObXEL-VR4E63mjgtnERkCflh1/view
  * Tested GET routes to return single category, single product, and single tag: https://drive.google.com/file/d/12J62BqbRtQs_Q3wgjNJbQmzMuzVYo-iT/view
  * Tested DELETE category by id, CREATE category, and UPDATE category: https://drive.google.com/file/d/1LC7actM3xBdePfi1A70SoAYyA_ULjo2D/view
  * tested DELETE, CREATE, and UPDATE for products and tags: https://drive.google.com/file/d/1Z5Ih2AbHpVEoUpldO6t-c1lV5AHC9wYv/view

## License

  [![mitLicense](https://img.shields.io/badge/license-MIT-green?style=plastic)](https://choosealicense.com/licenses/bsd-3-clause/)

## Questions

  [![GitHub](https://img.shields.io/badge/My%20GitHub-Click%20Me!-blueviolet?style=plastic&logo=GitHub)](https://github.com/itsnestor)

  Reach out to me at nestor.dejoya.campaner@gmail.com with any questions about the project.