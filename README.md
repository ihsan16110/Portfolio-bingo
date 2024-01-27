# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## 1/13/2024

## Project Building Scripts

## 1. npx create-react-app my-app

## 2. Removal of Unnecessary Files and Components

## a. Remove all unncecessary files[app.test.js, logo.svg,reportWebvitals.js, setupTests.js]

## b. Remove reportWebvitals import from reportWebvitals from index.js and reportWebvitals()

## c. Remove logo from App.js and the default div class inside retun () from functiom App()

## d. Clear App.css

## e. Clear Index.css

## 3. Installing Tailwindcsss in react project

## a. npm i -D tailwindcss

## b. npx tailwindcss init[created tailwind css config file]

## 4. Adding tailwind.config.js from Tailwind site documentation , and add that inside the content in tailwind.config.js

## a. content: ["./src/**/*.{js,jsx,ts,tsx}"],

## b. then Add the Tailwind directives to your CSS in tailwind.css file

## @tailwind base;

## @tailwind components;

## @tailwind utilities;

## 5. Adding colors inside the extend:{}

## extend:{

## colors: {

## primaryColor: "#8873ef",

## headingColor: "#081e21",

## smallTextColor: "#193256",

## },

## 6. Then installing

## a. npm i react-countup aos [react-countup -- it's a React component that creates animated number counters, aos --refers to Animate on Scroll (AOS), a lightweight and flexible library for adding smooth scrolling animations to web elements. ]

## 7. Then go inside the project sync-chron-new-website folder then open cmd or git bash then write Code .

## \***\* First Start of the New Project \*\***

## hit on terminal a. npm start build

## 8. a. npm i remixicon [to install remixicon library package]

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
