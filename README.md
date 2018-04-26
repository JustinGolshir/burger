# Eat Da Burger!
Burger logger application with MySQL, Node, Express, Handlebars and a homemade ORM. This application follows the MVC design pattern using Node and MySQL to query and route data in the application and Handlebars to generate the HTML.

## Description

* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.
* Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.
* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.
* The app will store every burger in a database, whether devoured or not.

## Application Architecture

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   ├── assets
│   │   ├── css
│   │   │   └── style.css
│   │   └── img
│   │       └── burger.png
│   └── test.html
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```

## Screenshot

![alt text](https://github.com/JustinGolshir/burger/blob/master/public/assets/images/BurgerApp.png "Burger App")

## Demo

The demo of the burger eating application can be found [here](https://burger-justgo.herokuapp.com/).

## Installation

To run the application locally, first clone this repository with the following command.

	git clone git@github.com:justingolshir/burger.git
	
Next, install the application dependencies.

    npm init
	npm install
    npm install express
    npm install express-handlebars
    npm install sequelize
    npm install mysql2
	
Finally, run the node server locally.

	node server.js
	
Now, open the local application on port 3000 at the URL: `http://localhost:3000/`.

**Enjoy and have a burger!**




