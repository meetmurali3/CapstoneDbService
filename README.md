# DB service for the insurance application. 
### Express based REST server for serving Postgres content using Sequelize node module

This is a service layer application and it contains HTTP endpoints. These endpoints use GET, POST, PATCH methods to support a frontend application.
These methods are decoupled from the frontend application and they serve the requests hitting them from any application. This uses sequelize ORM to interact with the database.

To start the server - Run `npm start` to start the server. If everything went right, you should see a message saying that the server was started and listenig on some port...
