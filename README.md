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


### QUESTIONS ASKED 

Ans 1 :  I have chosen mongoDb database here as it is a json databases and helps in maintaining proper realtionships and unstructured data .  Also it can be easily hosted as per the need

Ans 2 : The main thing I learned is maintaining relationships of data  , executing them  , writing proper queries , improving qeury time

Ans 3:  The most difficult part in the assignment was maintaining all the endpoints and controllers 

Ans 4 : I would have tried to optimize the code , reuse the controllers wherever possible , refine the data to minimize the data load wherever possible 