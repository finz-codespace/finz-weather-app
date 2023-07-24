# Weather App

This is a weather app that allows a user to login and display features to fetch current weather, and historical weather. It also allows the user to associate historical weather information with a real life event (for example: a vacation day), along with date-time information and retrieve it.

## Problem Statement
The goal is to build a weather app that has the following features: 

### Front End
1. Sign up Page that allows a user to setup first name, last name, email and password.
2. Login Page that allows an exiting user to login.
3. A landing page that shows the following: 
    - Some general user stats like, Full name (first name following by last name), date-time of last login, and login counts so far.
    - A weather widget that shows a few current weather data features, like temperature, precipitation, wind speed etc.
    - A panel for fetching historical weather data that allows the user to enter latitude, longitude, and date-time to fetch historical weather.

Please code the above frontend features using React components. 
- Keep the React frontend code separated from any backend functionality like calling weather API or interacting with database.
- For the initial iteration just create a set of frontend pages mentioned about without any backend functionality, for example, create the sign up and login pages where sign up / login buttons work without any user inputs and take you to a landing page that contains UI components which use hard coded values. If you want to use JSON objects behind your React components or maintain React state with the useState hook, hard code the backing JSON objects as per your requirements and use them in the state. 

### Backend
The backend will need to implement the following: 
- Registering and storing user information at the time of sign up. 
- Validating user and creating a user session at the time of login / signup.
- Calling the OpenWeatherMap API for fetching weather info. [OpenWeatherMap](https://openweathermap.org/api/one-call-3)

The specific details about how to use the [OpenWeatherMap](https://openweathermap.org/api/one-call-3) API will be published once you have completed and submitted the Frontend part of the assignment.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder.



