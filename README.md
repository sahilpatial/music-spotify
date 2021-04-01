To run this project, 

```
For Running this App your system must have these dependencies: axios@0.19.2 bootstrap@4.5.2 lodash@4.17.19 prop-types@15.7.2 react-bootstrap@1.3.0 redux@4.0.5 react-redux@7.2.1 react-router-dom@5.2.0 redux-thunk@2.3.0.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.
Open (http://localhost:3000) to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

This App is deployed on Firebase.
Link is: spotify-music-5762d.web.app

I have used the spotify-webApi here for fetching of the data.
In developer mode of spotidy after creating app, in the settings of the app i have put http://localhost:3000/redirect in the redirect url.
(After deploying my project on firebase I changed the redirect URL to https://spotify-music-5762d.web.app/redirect)

I have used the spotify's API for authentication purpose.
I have used REDUX for statemanagement.
With the help of spotify's search api , we can search any song, playlist or album and it will show up.

And if you want to play any song that showed up, after clicking on the song, album or playlist it takes us to the official spotify web player.




