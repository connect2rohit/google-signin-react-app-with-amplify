# To start implement google sign with amplify in a react app you need three things

Before starting with Aws Amplify, We need to set up 3 things.
Set up an AWS account.
Install the latest version of Node.js.
Install the latest version of NPM.

Once after setup these three basic requirement, you are good to go.

Open Command line and type the following command

npm install -g @aws-amplify/cli


1. First you need to add aws amplify npm package to your project
use command
 $  yarn add aws-amplify

2. Then run this command 
# $ amplify init
(The amplify init command is a one-time initialization step for your Amplify powered cloud app. You run this once for each project (JavaScript, iOS, or Android) to connect your app with an AWS backend.) to your project.

3. Use Command 
# $ amplify  add auth
to add authentication feature to your application. It will ask you couple of questions. You can see in the screen shot.
It will ask you couple of questions, answer as per you requirement.


4. To sync local backend resources with cloud execute 
# $ amplify push
command in your terminal.

# Setup your project in google dveloper console, here are the steps
Go to Google Developer Console
Create a new project.
Now, create Credentials.
Save these Client id and Secret key , we need them to connect with AWS user pool
Configure consent screen.
Now, choose Credentials.
Select the client you created in the first step and click the edit button.
Type your user pool domain into Authorized Javascript origins.
Type your user pool domain with the /oauth2/idpresponse endpoint into Authorized Redirect URIs.
https://docs.amplify.aws/lib/auth/social/q/platform/js/#setup-your-auth-provider









# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

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

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
