# Random Playlist Generator

## About The Project
This is a web application that allows users to generate a random playlist of songs based on various filters such as their likes, the year, genre, and duration of the playlist. The app uses HTML, CSS, and JavaScript on the frontend, with React as the frontend framework. On the backend, it uses Express, Node.js, mysql, and Sequelize, following the MVC architecture pattern.

The app allows users to input their preferences such as the genre, year, and the number of songs they want in the playlist. It then uses an API to fetch data about songs matching the given criteria and generates a playlist. The user can then save the playlist or generate a new one.

The backend server defines API routes for handling the various requests made by the client. It also defines controllers that handle the logic for generating the playlists and fetching data from the database.

## Built With
* HTML
* CSS
* JavaScript
* Express
* Node.js
* mysql
* Sequelize
* APIs

## Getting Started
To access this project, visit the repository link: https://github.com/andrewbreytenbach/random-playlist-generator

Heroku Deployment: https://new-random-playlist-generator.herokuapp.com/

To get a local copy up and running, clone this repository to your local machine and run npm install to install the necessary dependencies. You will also need to set up a MySQL database and update the config.json file with your database credentials. Run npm run start to start the server and navigate to your local port to use the app.

## Usage
To generate a playlist, the user selects their preferences such as the genre, artist. The app then generates a playlist based on these criteria and displays it to the user. The user can then choose to save the playlist or generate a new one. The songs will also be playable immediately on the page.

Login Page Screenshot: ![](./public/images/login.png)

Homepage Screenshot: ![](./public/images/homepage.png)

## Contact
* [https://github.com/andrewbreytenbach] (Andrew Breytenbach)
* [https://github.com/jonparker1221] (Jon Parker)
* [https://github.com/graysont3] (Taja Grayson)
* [https://github.com/KritiShrestha] (Kriti Shrestha)
* [https://github.com/emiles55] (Emily Miles)

## Acknowledgments
* [https://expressjs.com/] (Express Documentation)
* [https://sequelize.org/master/] (Sequelize Documentation)
* [https://www.npmjs.com/] (NPM Documentation)
* [https://github.com/jordantwells42/vibesition] (Vibesition)
* [https://developer.spotify.com/] (Spotify API)