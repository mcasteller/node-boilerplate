# Node web server bolierplate

It contains initial folder structure to start developing a Node Restful API. So far it only deals with user authentication API.

Technologies

-  NodeJS (await, async functions)
-  Express
-  MongoDB database (mongoose)
-  Jest test tool.

## Required Tools
    [Node.JS](https://nodejs.org/en/)
    [npm](https://www.npm.com/) 

## Installation
Go to the project root folder and run
```
npn install
```

## Environment variables set up using node-config module
You can use config module file named custom-environment-variables.json to set up 'BOILERPLATE_JWT_PRIVATE_KEY' environment variable (set/export on windows/mac). Example: 
```
export BOILERPLATE_JWT_PRIVATE_KEY=mySecureKey
```
Config module is responsible for dealing with these variables, info in here: (https://github.com/lorenwest/node-config/wiki/Environment-Variables)

## Usage
To run this project into a local server run
```
node index.js
```

## MongoDB Atlas
Create a Database/Cluster
Create user and define readWrite rol.

## Some interesting topics you may find

- NodeJS Restful services, async methods

- Mongoose 

- JWT token for user authentication

- Jest, supertest for testing

- Lodash (simil underscore)

- Winston logging tool

- Joi - Object server side validation

## Project Structure

- /config: where config resources met (npm config-module)
  
- /middleware: middleware modules

- /models: mongoDB schema and model deinitions 

- /routes: modular route behaviour

- /startup: modular logic called on app start up

- /test: test cases (integration and unit tests)

- Other configuration files
  - package.json: node/yarn dependency list
