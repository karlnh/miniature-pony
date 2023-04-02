# miniature-pony

## Description
E-Commerce backend using CRUD operations to organize products. Makes use of MySQL, Express, and Sequelize to put products in categories and give them tags.

This project was a test in relating different SQL tables together to create, retrieve, update, and delete relational data, by means of data models and api routes for each operation.

## Installation
Once the repo is downloaded annd you have installed the required Node packages, open a MySQL shell and type `SOURCE db/schema.sql` to create the database schema.

Then use `npm run seed` to seed the database with data.

After that, run `npm run start` to start the server normally.

If you want to change the files, run `npm run watch` to create a nodemon instance which watches for updates to the files and restarts the server as necessary.

Open something like Insomnia or Postman to easily make testable routes so you can access the data you've just made. For instance, `http://localhost:3001/api/products/6` will access the product with the product id '6'.

## Usage
![example video]()

## License
Using the GGPLv3. See the LICENSE file for more detail.