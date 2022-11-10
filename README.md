# NASA Mission Control Project
This is a NASA space dashboard project which uses **REACT.JS + NODE.JS and MONGODB technology** to build this application. The front-end part of the code was a template used in a udemy course.  The back-end part of the project is build from scratch!

## Getting Started

1. Ensure you have Node.js installed.
2. Create a free [Mongo Atlas](https://www.mongodb.com/atlas/database) database online or start a local MongoDB database.
3. Create a `server/.env` file with a `MONGO_URL` property set to your MongoDB connection string.
4. In the terminal, run: `npm install`

## Running the Project

1. In the terminal, run: `npm run deploy`
2. Browse to the mission control frontend at [localhost:8000](http://localhost:8000) and schedule an interstellar launch!

## Docker

1. Ensure you have the latest version of Docker installed
2. Run `docker build -t nasa-project .`
3. Run `docker run -it -p 8000:8000 nasa-project`

## Running the Tests

To run any automated tests, run `npm test`. This will: 
* Run all the client-side tests: `npm test --prefix client`
* Run all the server-side tests: `npm test --prefix server` 

## Project images

![1](result-images/1.png)

![2](result-images/2.png)

![3](result-images/3.png)

![4](result-images/4.png)

![5](result-images/5.png)

![6](result-images/6.png)
