# Weather App

This is a weather app that allows a user to login and display features to fetch current weather, and historical weather. It also allows the user to associate historical weather information with a real life event (for example: a vacation day), along with date-time information and retrieve it.

## Problem Statement
The goal is to build a weather app that has the following features: 

### Front End (Included in the Assignment)
1. Sign up Page that allows a user to setup first name, last name, email and password.
2. Login Page that allows an exiting user to login.
3. A landing page that shows the following: 
    - Some general user stats like, Full name (first name followed by last name), date-time of last login, and login counts so far.
    - A weather widget that shows a few current weather data features, like temperature, precipitation, wind speed etc.
    - A panel for fetching historical weather data that allows the user to enter latitude, longitude, and date-time to fetch historical weather.

Please code the above frontend features using React components. 
- Keep the React frontend code separated from any backend functionality like calling weather API or interacting with database.
- For the initial iteration just create a set of frontend pages mentioned about without any backend functionality, for example, create the sign up and login pages where sign up / login buttons work without any user inputs and take you to a landing page that contains UI components which use hard coded values. If you want to use JSON objects behind your React components or maintain React state with the useState hook, hard code the backing JSON objects as per your requirements and use them in the state. 

**Note**: Please note that the Backend of this app does not exist as of now. Please make necessary assmptions while developing the Frontend React app and use mocking to simulate any backend APIs you feel would be required. For example you can consider the use of [Mock JSON Server](https://www.npmjs.com/package/json-server), for mocking the backend.

## Submitting Instructions
Please follow the below steps to complete and submit this assignment - 
1. Provide us your GitHub username / profile, if you do not have a GitHub account create a new one (You must have already done this when you submitted the main form before starting with this assignment).
2. Login to your own GitHub account, Navigate to this repository by searching for **_finz-whether-app_** repository on github. ![image](https://github.com/finz-codespace/finz-weather-app/assets/138383712/556b3d68-2a90-4e33-8b3a-3a37afa5fc56)

3. Navigate to this repository and create your own **Private** Git repository by using this finz-weather-app repo as a Template. Please see the screenshot below. ![image](https://github.com/finz-codespace/finz-weather-app/assets/138383712/bda7a352-f7a7-47d4-b352-4d76506786f4)

4. Please make sure that you create a **Private** respository, as shown in this screenshot. ![image](https://github.com/finz-codespace/finz-weather-app/assets/138383712/e6a32626-9528-45d2-9471-306cc13c5169)
5. Once the repository is created you need to add Finz as a collaborator in it. You can do that by going into your GitHub repository's settings as follows.
   - Navigate to Settings --> Collaborators. ![image](https://github.com/finz-codespace/finz-weather-app/assets/138383712/32ed1f9f-1827-4a39-8638-41d7892678f2)
   - Add People under Collaborators menu. ![image](https://github.com/finz-codespace/finz-weather-app/assets/138383712/4a9e5705-9213-4363-ae9e-c36f7b78321e)
   - When you click on Add People, an account search pop-up will open, please key in the value 'finz-codespace' and select the suggestion that appears in the drop down. ![image](https://github.com/finz-codespace/finz-weather-app/assets/138383712/a128331c-ab5d-4f5d-bd66-c96c382bbcba). And click on 'Add finz-codespace to this repository'.
   - You will see that finz-codespace is added in a 'Pending Invite' state. This invitation will come to the Finz github account.
   - Once we accept the invitation we will be able to access your work in your private repository.

Once you have done the above setup, you are ready to start working on the assignment.

**Note**: We recommend that you use GitHub codespaces with this newly created private repo which comes installed with VSCode and npm utlilities. Please check the CodeSpaces pricing policy before using it. It is generally Free for some minimum hours per month.

Happy Coding!!

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



