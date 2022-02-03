# mern

Tutorial to create similar web app here: https://www.mongodb.com/languages/mern-stack-tutorial

**Server Dependencies**
* mongodb: drivers to allow NodeJS app to connect to db
* express: web framework for NodeJS
* cors: NodeJS package that allows for cross origin resource sharing (HTTP-header based mechanism that allows a server to indicate any origins (domain, scheme, or port) other than its own from which a browser should permit loading resources)
* dotenv: module that loads environment variables from .env file to process.env file --> separate config files from code

*Server notes*
* server.js is the main body that calls the other files/dependencies
* routes (record.js) allow the db to be read/modified by the server
* conn.js establishes a connection to the mongodb database

**Client Dependencies**
* bootstrap: preset templates/components for web apps
* react-router-dom: React router components for web apps