This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Context
Stolen bikes are a typical problem in Berlin. The Police want to be more efficient in resolving stolen bike cases. They decided to build a software that can automate their processes — the software that you're going to develop.

This app needs to display the list of reported bike thefts based on the Bikewise API.

## Demo
https://bikeindex-b3100.firebaseapp.com/

## Product Requirements
As a police officer:

 -> I want to see a list of reported bike thefts for the Berlin area.
 
 -> I want to see the first 10 bike theft cases, with the ability to - paginate (10 cases per page).
 
 -> I want to see a total number of bike theft cases.
 
 For each reported bike theft I want to see:
 
 -> Case title
 
 -> Case description
 
 -> Date of the theft
 
 -> Date of when the case was reported
 
 -> Location of the theft
 
 -> Picture of the bike, if available
 
 -> I want to filter reported bike thefts by partial case title.
 
 -> I want to filter reported bike thefts by date range.
 
 -> I want to see a loading state until the list is available.
 
 -> I want to see an error state if the list is unavailable.
 
 -> I want to see an empty state if there are no results.

## Packages Used
Redux,
Redux-Saga,
Typescript,
Lodash,
Moment,
Moment-Timezone,
Jest,
Enzyme,
Axios,
Styled-Components ecosystem

## Testing
I have integrated unit using jest, enzyme. 
To test unit testing using jest and enzyme command is: 'yarn test'

## Configuration
Please find axios-incidents.ts file in the project to set api base url to access api using axios.

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

## MIT License

Copyright (c) 2019 Shahriat Hossain
