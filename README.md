# E-commerce Back End

## Table-of-Contents

- [E-commerce Back End](#e-commerce-back-end)
  - [Table-of-Contents](#table-of-contents)
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Screenshot](#screenshot)
  - [Questions](#questions)


## [Description](#table-of-contents)
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

## [Installation](#table-of-contents)
`git clone` the repo to your local machine. 

Once cloned, run the following command in your terminal:

`npm install`.

And then run the following commands to install the dependencies: 

`npm i inquirer`

`npm i sequelize`

`npm i dotenv`

`npm i express`


## [Usage](#table-of-contents)

Type the following command in your termimal:
`mysql -u root -p` -- connect to your database and then run: 

`source schema.sql`

Quit mySQL shell. Run the following command to seed the files:

`npm run seed`.

Then run:

`npm start`

## [Screenshot](#table-of-contents)
![Screenshot of App](/Assets/Screenshot%202023-09-18%20at%204.13.46%20PM.png)

[Walkthrough Video](https://drive.google.com/file/d/1eI6qkvNQZBdBcLHkX1dhG_Rjbw7puLVP/view)

## [Questions](#table-of-contents)

Please contact me with any questions!

Contact information:

[GitHub](https://github.com/PeterJanasz/E-commerce-Back-End)

[Email: petertjanasz@gmail.com](mailto:petertjanasz@gmail.com)


