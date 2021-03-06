# The Quick Way to Create a New React App

Create React App is the best way to start building a new React single page application. It sets up your development environment 
so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production. 
You’ll need to have Node >= 6 on your machine.

Full instructions can be found in the readme of the Github repo: https://github.com/facebookincubator/create-react-app

```
Install
> npm install -g create-react-app  // set up global access - only done once

CREATE a new app repo that uses "create-react-app"
> create-react-app repo-name
> cd repo-name
> npm start
```
http://localhost:3000/ should open automatically in your browser and you should see your app.

When you’re ready to deploy to production, create a minified bundle with 
```npm run build```

Create React App doesn’t handle backend logic or databases; it just creates a frontend build pipeline, so you can use it with any backend you want. It uses build tools like Babel and webpack under the hood, but works with zero configuration.

When you’re ready to deploy to production, running npm run build will create an optimized build of your app in the build folder. You can learn more about Create React App from its README and the [User Guide] https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#table-of-contents.

npm commands available:
```
 npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!
```
