# Assignment
Nodejs backend server for menu management. 
The menu will be divided into 3 parts in the following order:
Category
Sub Category: A category can have multiple sub-categories
Items: A Subcategory can have multiple items in it

## Features

- Create, read, and update items, categories and subcategories.
- MongoDB Atlas integration.
- Environment variable configuration.

## Create a .env file in the root directory of your project and add the following environment variables:
    MONGODB_URL=mongoDb_url
    PORT_NO=3000


### Running the Application
    ```sh
    npm i 
    npm start

