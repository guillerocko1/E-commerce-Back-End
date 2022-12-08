# E-commerce-Back-End


## Table of Contents

- [GET All Categories](#GET-All-Categories)
- [GET A Specific Category](#GET-Spcific-Category)
- [POST](#POST)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

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

The following link will show the way to run POST adding a new Category.


![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_POST.png?raw=true)]


### GET

Running the app in Visual Studio code (node server), opening Insomnia, selecting the option GET, and speicfying the link localhost:3001/api/categories, in the local server Insomnia will shows the Information about all the categories stored in the table categories in our Database.

The same Information will be shown using GET routes to return all categories, all products, and all tags being tested in Insomnia Core.

For example the root localhost/3001/categories will show all the data stored in the table categories. The image in the following link shows the information shown to the user from the local server in insomnia.


![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_ALL.png?raw=true)]


### GET

Running the app in Visual Studio code (node server), opening Insomnia, selecting the option GET, and speicfying the link localhost:3001/api/categories, in the local server Insomnia will shows the Information about all the categories stored in the table categories in our Database.

The same Information will be shown using GET routes to return all categories, all products, and all tags being tested in Insomnia Core.

For example the root localhost/3001/categories will show all the data stored in the table categories. The image in the following link shows the information shown to the user from the local server in insomnia.


![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_ALL.png?raw=true)]


### GET

Running the app in Visual Studio code (node server), opening Insomnia, selecting the option GET, and speicfying the link localhost:3001/api/categories, in the local server Insomnia will shows the Information about all the categories stored in the table categories in our Database.

The same Information will be shown using GET routes to return all categories, all products, and all tags being tested in Insomnia Core.

For example the root localhost/3001/categories will show all the data stored in the table categories. The image in the following link shows the information shown to the user from the local server in insomnia.


![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_ALL.png?raw=true)]


### GET

Running the app in Visual Studio code (node server), opening Insomnia, selecting the option GET, and speicfying the link localhost:3001/api/categories, in the local server Insomnia will shows the Information about all the categories stored in the table categories in our Database.

The same Information will be shown using GET routes to return all categories, all products, and all tags being tested in Insomnia Core.

For example the root localhost/3001/categories will show all the data stored in the table categories. The image in the following link shows the information shown to the user from the local server in insomnia.


![result_screen][(https://github.com/guillerocko1/E-commerce-Back-End/blob//main/API_ALL.png?raw=true)]

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
