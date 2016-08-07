# Introduction


This is a very basic nodejs hapi server for the purpose of giving a 
demo of my coding ability. This is the first time I am building a hapi
nodejs server and have written it from scratch. The time taken to complete
this project was about 2 days.

The main goal of the project is to parse a markdown and convert it to
equivalent html representation.


# Setup

## Install software


The project has following dependencies :-

* node version 6.2.2 or above (uses generators and es6 classes)
* mongodb version 3.2 or above


## Setup database

If you are running the server locally on your machine, you would need to start a mongodb server. Ex,

```
mongodb sudo mongod --dbpath /data
```

If using an external DB, then you can mongodb database using environment variable
DB_URI. Ex,

```
export DB_URI=mongodb://user:password@host:port/database
```

## Run testcases

* `npm test` will run all testcases
* `npm run test-converter` will run testcases for markdown converter utility
* `npm run test-api` will run testcases for the api

## Run the server

```
npm start
```
