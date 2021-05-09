# Tech Blog

## Links

## Description
This is a CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. This app uses Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

## Installation
To install this for local testing:

1. Make sure you have [node.js](https://nodejs.dev/) installed on your local machine.
2. Next clone this repository. Navigate to the root directory of the copy in your terminal and run the following commands:
```
    npm install
```
3. You will then need to create a MySQL database either through a program such as MySQL Workbench. An `.sql` file to run the query is available in `/db` file.
4. You will then need to create and set up a `.env` file with the following information:
```
    DB_NAME=techblog_db
    DB_USER=  // Your MySQL username here (typically root)
    DB_PASS=  // Your MySQL password here
```
5. Now to seed the database with some example data, return to your root directory of the repo, and run:
```
    npm run seed
```
6. Finally, run the following to start the server:
```
    npm start
```

## Screenshots
