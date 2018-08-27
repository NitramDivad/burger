# ** Node Express Handlebars:  Eat-Da-Burger!
#

Eat-Da-Burger App Details


In this activity, I was tasked to create a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. Th MVC design pattern is utilized along with Node and MySQL to query and route data in the app, and Handlebars to generate your HTML.  The application was also deployed to Heroku.

The app is structured so that user input is as simple as submitting a burger choice.  That choice will saved to the MySQL database per the following schema:

    * id: integer data type not null; primary key
    * burger_name: varchar(255) data type not null
    * devoured: boolean data type; default value = false (0)
    * createdAt: timestamp data type; default value = current timestamp

When a burger is submitted, it is added to the "Burgers to Devour" list on the left hand side, along with a button labelled "Devour It!".  The name of the burger will be populated to the burger_name DB table column with a false value assigned to the devoured column.  As well, the id column will be incremented and updated along with the createdAt column being assigned the current timestamp.

When the "Devour It!" button is clicked, the burger will be removed from the "Burgers to Devour" list and will be added to the "Devoured Burgers" list on the right hand side.  Additionally, the "devoured" DB table column will be updated with a value of true (1).



## **Created by:** #

[David Martin](mailto:webdevelopment.du@gmail.com)

## **Links:** #

| [Eat-Da-Burger Site](https://fierce-tor-40499.herokuapp.com) | 
[Portfolio Site](https://nitramdivad.github.io/) | 
[GitHub](https://github.com/nitramdivad) |