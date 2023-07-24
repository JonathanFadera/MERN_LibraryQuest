# MERN_LibraryQuest

## Description

This Book Search Website allows users to search for books and explore their titles, descriptions, authors, and cover images. The website utilizes the Google Books API to retrieve comprehensive information about books, and users can easily navigate to the respective entries on Google Books for more details. The site offers a seamless experience where users can freely search for books without needing an account. However, to leverage additional features like saving favorite books to a personalized collection, users have the option to create an account.

## Table of Contents

  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Mock Up](#mock-up)
  - [Credits](#credits)
  - [Access](#access)

## Installation

This application requires a number of packages (see [Credits](#credits) below for more information). To install these packages, clone the repo, `cd` into it, then run the command `npm i`.

Instructions for using the application:
- If you do not have an account and wish to save books, first create an account:
    - Click "Login/Sign Up" at the top-right corner
    - Click the "Sign Up" tab in the modal that appears
    - Enter a username, email, and password and then click "Submit"
- If you have an account and wish to log in, click "Login/Sign Up" and enter your login credentials
- The Home page contains a search bar to look up books. Enter your search term and click "Submit Search". Note you do not have to be logged in to search but you do have to be logged in to save books.
    - Click on "View book on Google Books" to navigate to the Google Books webpage for the book.
    - If you are logged in, click "Save this Book!" to save the book to your account.
- If you are logged in, click "See Your Books" in the navigation menu to view your saved books.
    - Click "Delete this Book!" to remove a book from your saved books.
- You will be automatically logged out after a period of inactivity, or you can click "Logout" in the top-right corner to log out

## Mock Up

![Screenshot of application showing search bar and search results](./Screenshot%202023-07-24%20at%2012.45.47%20AM.png)

## Credits

[Starter code](https://github.com/coding-boot-camp/solid-broccoli) was provided by the UC Berkeley Coding Boot Camp.

The following packages are used in this application:
- Front-end:
    - [@apollo/client](https://www.apollographql.com/docs/react/) to interact with the GraphQL server
    - [bootstrap](https://getbootstrap.com/) to style the application
    - [graphql](https://graphql.org/) to handle APIs and querying
    - [jwt-decode](https://www.npmjs.com/package/jwt-decode) to decode JSON Web Tokens
    - [react](https://react.dev/) / [react-bootstrap](https://react-bootstrap.netlify.app/) / [react-router-dom](https://www.npmjs.com/package/react-router-dom) / [react-scripts](https://www.npmjs.com/package/react-scripts) to build the front-end

 - Back-end:
    - [express](https://www.npmjs.com/package/express) to build the server
    - [bcrypt](https://www.npmjs.com/package/bcrypt) to hash passwords
    - [apollo-server-express](https://www.npmjs.com/package/apollo-server-express) to build the GraphQL server
    - [graphql](https://graphql.org/) to handle APIs and querying
    - [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) to generate JSON Web Tokens
    - [mongoose](https://www.npmjs.com/package/mongoose) to interact with the MongoDB database

## Access
Ready to explore? Visit my repository and immerse yourself in a world of tech wonders!
[Click here to view the repository.](https://github.com/JonathanFadera)

To experience the live version, head over to the deployed Heroku link and join the tech enthusiasts' community.
[Click here for the Deployed Heroku Link.](https://boiling-ridge-41335-056f47e4c277.herokuapp.com/)



Join me on this exhilarating tech journey, and together, let's shape the future of technology!
