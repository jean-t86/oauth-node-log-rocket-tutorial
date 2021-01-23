# OAuth 2.0 with Express.js and PostgreSQL tutorial from Log Rocket 
## Table of contents
* [General information](#general-information)
* [Technologies](#technologies)
* [Following along](#following-along)
* [Setup](#setup)
* [Run the web server locally](#run-the-web-server-locally)

## General Information
This code repository contains the completed [tutorial](https://blog.logrocket.com/implementing-oauth-2-0-in-node-js/) from Log Rocket on building an OAuth 2.0 Authorization server using Express.js. 

It is not an exhaustive implementation of OAuth 2.0, but is an ideal tutorial to get a quick overview of what is needed in the most basic of [flows](https://auth0.com/docs/authorization/which-oauth-2-0-flow-should-i-use).

## Technologies
* JavaScript
* Node.js
* Express.js
* PostgreSQL
* node-oauth2-server (npm package)

## Follow along
If you are interested in following along with the tutorial, there are a few additional information/ corrections that will make it easier for you.

### Install PostgreSQL on your machine
Follow the link to [install PostgreSQL](https://www.postgresql.org/) on your machine.

### Create the database

Enter the psql terminal:

```
sudo -u postgres psql postgres
```

Create the database:

```
CREATE DATABASE logrocket_oauth2;
```

Switch to the newly created database:

```
\c logrocket_oauth2;
```

We can then continue on with creating the tables for the database as intructed in the tutorial.

## Setup

If you want to run the web server locally, you first need to install Node.js on your computer:
* [Download](https://nodejs.org/en/download/) the binaries
* If you use Linux, follow the [installation instructions](https://github.com/nodejs/help/wiki/Installation#how-to-install-nodejs-via-binary-archive-on-linux).

Once installed, install the program's dependencies with 
```
npm install
``` 
in your terminal with the project's folder as working directory.

## Run the web server locally

You can start the server using
```
node index.js
```

The web server will start and be reachable at `http://localhost:3000`
