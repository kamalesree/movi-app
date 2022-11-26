# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.



# Overview

Simple fullstack web application that displays a list of movies and movie details.

Within this Glitch project is an existing application boilerplate (React + Node), but you are free to modify it as you want to.

Feel free to also download the project and work on it in localhost if you prefer to.

# Steps

1. Within Glitch, click on `Remix to Edit` to start own forked version of the code
2. Start editing code within Glitch to complete this assignment

# Details

* The backend server should load data from the movies data file found in `server/movies_metadata.json`.
* The backend server should expose APIs to the frontend to achieve the following:
  * List movies
  * Get single movie by ID
* The frontend web application should display 2 different screens:
  * List movies page (shown initially)
    * Display the following fields (`title`, `tagline` and `vote_average` [calculated out of 10]) with **responsive web design** (e.g. show 4 columns on a desktop but show only 1 column on a mobile device)
  * Display single movie page upon clicking movie in list page
    * Display every field (`release_date` should be localized based on browser settings. `runtime` is calculated in minutes)
    * Display a button/link to return to list movies page





[create-react-app]: https://create-react-app.dev
[Express]: https://expressjs.com/e

