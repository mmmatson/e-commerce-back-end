# E-Commerce Back End

## Description

In this repository I built the back end for an e-commerce site by modifying starter code. I configured a working Express.js API to use sequalize to interact with a MySQL database.

I used [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect my Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data (like MySQL username, password, and database name).

## Installation

  1. Fork the repository so that you have a local copy saved on your computer.
  2. Navigate to the forked repository on your computer using your command line application.
  3. Navigate to the "db" folder, then enter "source schema.sql" in MySQL shell to create the "ecommerce_db" database.
  4. (Optional) Enter "npm run seed" in your command line application to seed the database.
  5. Navigate to the main "e-commerce-back-end" repository folder, then enter 'node server.js' in the command line application to sync the sequelize models to the database and turn on the server.

## Usage

[E-Commerce Back End Video Demo](https://watch.screencastify.com/v/Tlm6w1Req13YI9ic1LVW)

![E-Commerce Back End Video Demo](assets/videos/e-commerce-back-end-demo-video.webm)

Use the application to CRUD categories, tags, and products.

## Credits

N/A

## License

See repository for license information.