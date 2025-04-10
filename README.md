# Prerequisites
Before you begin, ensure you have the following installed:

Node.js (v14 or later recommended) - for running the backend and frontend.
npm (Node Package Manager) - comes with Node.js.
Jira Account - Required for OAuth and Jira API access.

# TypeScript Support

This project is built with TypeScript to ensure type safety, improve maintainability, and catch potential issues early during development.

# The following essential files are TypeScript-based:

tsconfig.json: Configuration file for TypeScript.
Home.tsx: Contains TypeScript types for form fields, props, and hooks.

# To clone the Repo 
git clone <repository-url>
cd <repository-name>
Run npm install after cloning under backend,frontend and frontend/src directory

# Set up env file
CLIENT_ID=your-client-id
CLIENT_SECRET=your-client-secret
REDIRECT_URI=http://localhost:4000/oauth/callback
JIRA_API_URL=https://your-instance.atlassian.net

# To start backend 
npm run dev

# Endpoints available:

GET /oauth/start: Redirects to Jira's OAuth authorization URL.
GET /oauth/callback: Handles the callback from Jira after OAuth.
POST /create-issue: Endpoint to create Jira issues using the received access token.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

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

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).