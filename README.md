# TodoApp Repository
This is a TodoApp Application using Node.js and MongoDB

Open Visual Studio and in PowerShell execute the commands

Created directory TodoApp 

Initiate the npm modules : npm init # Creating the default package.json file 

Installing the packages and saved as dependecies with the project.json file :
Express Mongoose ejs dotenv

Express is a popular framework for building and running node.js application.

Mongoose is a MongoDB object modelling tool design to work in the asynchronous environment.

Nodemon is also installed as development dependency as it automatically starts the node.js application whenever there is a file changes are made in the directory are detected.

ejs is a tool that allows to generate webpages that include dynamic data and those template pieces can be used in other webpages.

dotenv file is a simple text configuration file for controlling the applications environment constants. It lets us to customize the individual working environment.

MongoDB account to create so that we can store the JSON documents as it is NOSQL or non-relational database.

In index.js file :

All the other files has been executed for the running of Web application.

All the packages are imported and assigned to constants.

TodoTask.js is to add the scheme which is created in the MongoDB database and applied in GET and POST method of index.js file

.env file for MongoDB connection is created and configured in index.js file.

todo.ejs , todoEdit.js and style.css are the webpages tools and templates, that is used in CRUD operations of index.js file.

So, basically i have created a web application with the TodoApp, where we can make a list of things to do and even we can edit and delete as necessary.




