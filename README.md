### Folder Structure

- node-mysql-crud-app (main directory)
    - node_modules
    - public
        - assets
            - img
    - routes
        - index.js
        - player.js
    - views
        - partials
            - header.ejs
        - index.ejs
        - add-player.ejs
        - edit-player.ejs
    - app.js


### Install Required Modules

- express: Used to create and handle routing and process requests from the client.
- express-fileupload: Simple express file upload middleware that wraps around busboy.
- body-parser: Used to parse incoming request from the client.
- mysql: node JS driver for MySQL.
- ejs: templating engine to render html pages for the app.
- req-flash: Used to send flash messages to the view.
- nodemon: Installed globally. It is used to watch for changes to files and automatically restart the server.

The following command will install the 7 modules as dependencies.
``npm install express express-fileupload body-parser mysql ejs req-flash --save``

Install nodemon globally:
``npm install nodemon -g``

To run the server:
``nodemon app.js``

Access the app on:
[http://localhost:500](http://localhost:500)