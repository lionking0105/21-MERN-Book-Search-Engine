## 21 MERN: Book Search Engine

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This project is to take the starter code with a fully functioning Google Books API search engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server. The application was built using the MERN stack with a React front end, MongoDB database, Node.js, Express.js and API and was already set up to allow the users to save book searches to the back end.

This project assisgnment is to :-

- Set up an Apollo Server to use GraphQL queries and muations to fetch and modify data, replacing the existing RESTful API.
- Modify the existing authenication middleware so that it works in the context of a GraphQL API.
- Create an Apollo Provider so that requests can communicate with an Apollo Server.
- Deploy the application to Heroku with a MongoDB database using MongoDB Atlas.

The URL of the GitHub repository is https://github.com/stellalph/21-MERN-Book-Search-Engine.git and the repository name is 21-MERN-Book-Search-Engine.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Usage](#usage)
- [References](#references)
- [License](#license)

## Technologies Used

- This application is a MERN stack application which is a group of four technologies, that is:-
  - MongoDB
  - Express.js
  - ReactJS
  - Node.js
- The MERN stack has a three-layer architecture based on Model-View-Controller pattern and each interconnected layer performs a specific function in the application:-

  | Client (View)      | React JS               | User inputs data and Data display                    |
  | ------------------ | ---------------------- | ---------------------------------------------------- |
  |**Server(Controller)** | **Express.js and Node.js** | **Method called to store and retrieve data in database** |
  | Database(Model)    | MongoDB                | Stores raw data and contains no logic                |
 

- As this application has come already with mostly pre-installed npm packages and is fully functioning Google Books API search engine built with a RESTful API and to refactor it to be a Graph API built with Apollo Server, the following additional npm packages were installed:-

## Deployment

- The application has been deployed to Heroku with a MongoDB database using MongoDB Atlas.

- See the below the example of MongoDB database using MongoDB Atlas:-

  ![alt text](./assets/img05.png)

- The URL of the functional deployed application is https://protected-brushlands-99995.herokuapp.com/

## Usage

## References

## License

This project is licensed under the terms of the MIT license
