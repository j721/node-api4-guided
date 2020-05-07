# Web API Deployment Challenge

Guided project for **Web API IV** module.

In this project we will learn how to deploy a Web API to `heroku`.

## Prerequisites

- Sign up for a [heroku](https://www.heroku.com/) free account.

## Instructions

Please fork this repository and follow along **using your fork** as the instructor deploys the API to `heroku`.


##Environment Variables

Each developer must configure the following environment
variables

-API_SECRET is used to restrict access to the POST `/api/shouts` endpoints 

##Deployment
-make the PORT dynamic. Read the port from the environment
-provide the "start" scrip in `package.json` that uses `node`
to run the API. Heroku will run your application user `npm start`
-create new application on heroku
-connect it to branch to be deployed from repository on GitHub.