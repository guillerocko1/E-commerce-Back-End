# E-commerce-Back-End


## Table of Contents

- [GET All Categories](#GET-All-Categories)
- [GET A Specific Category](#GET-Spcific-Category)
- [POST](#POST)
- [PUT](#PUT)
- [DELETE](#DELETE)


## E-commerce-Back-End

To build this application we need to use the MySQL2 Links to an external site and Sequelize Links to an external site packages  as well to connect the Express.js API to a MySQL database and the dotenv package Links to an external site to use environment variables to store sensitive data, like our MySQL username, password, and database name.

Use the schema.sql file in the db folder to create the database using MySQL shell commands. Use environment variables to store sensitive data, like the MySQL username, password, and database name.

This application allows to the user to feed a Database running the seeds/index.js file and it can seen in MySql using the app MySQLWorkBench. After that the user can run each API to see the information in Insomnia.


### GET All categories

Running the app in Visual Studio code (node server), opening Insomnia, selecting the option GET, and speicfying the link localhost:3001/api/categories, in the local server Insomnia will shows the Information about all the categories stored in the table categories in our Database.

The same Information will be shown using GET routes to return all categories, all products, and all tags being tested in Insomnia Core.

For example the root localhost/3001/categories will show all the data stored in the table categories. The image in the following link shows the information shown to the user from the local server in insomnia.


![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_ALL.png?raw=true)]


### GET Spcific Category

Running the app in Visual Studio code (node server), opening Insomnia, selecting the option GET, and speicfying the link localhost:3001/api/categories/1, the user will get the information about a the cateogory with the ID 1.

The same Information will be shown using GET routes to return a spcific product, and a spcific tag being tested in Insomnia Core.

For example the root localhost/3001/category/1 will show the information of a spcific category. The image in the following link shows the information shown to the user from the local server in insomnia.


![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_Categories:6.png?raw=true)]


### POST

POST let us add an item to out Database. For example: In Insomnia, when we use POST, select JSON Option and add the code 
{
  "category_name": "Yellow"
}

As a result, we will add one cateogry to the table Categoiries and it will get automatically the ID.

The following link will show you running POST in Insomnia, adding a new Category.


![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_POST.png?raw=true)]


### PUT

Running PUT in Insomnia, will let the user to Update any data in the Database. The code added in Insomnia is basically the same than using POST.
We select the option JSON, and we will add the information about the data we want to update.
For example, if we want to update the Category with the ID: 6 the code would be the following.

{
  "category_name": "New name of the category"
}

Once, we run the API, Insomnia will shows that one row in the table has been updated. The following link shows how Insomnia looks after running the API.

![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_PUT.png?raw=true)]


### DELETE

To run the DELETE API, it is necessary to specify the ID of the item to delete. For exmple if the user wants to delete the product with ID number 1, the user needs to enter the following root. localhost/3001/api/products/1, then, select the option DELETE in Insomnia and run the API. Once, Insomnia execute the API and find the product with specified ID, the product is deleted.

The followong link shows how Insomnia looks when the user execute the DELETE API.

![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_DELETE.png?raw=true)]



## Author

Github Link: https://github.com/guillerocko1

E-commerce-Back-End Repository: https://github.com/guillerocko1/E-commerce-Back-End


