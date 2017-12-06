# Creating a New Application

Create React App is the best way to start building a new React single page application. It sets up your development environment 
so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production. 
You’ll need to have Node >= 6 on your machine.
```
npm install -g create-react-app
create-react-app repo-name

cd repo-name
npm start
```

Create React App doesn’t handle backend logic or databases; it just creates a frontend build pipeline, so you can use it with any backend you want. It uses build tools like Babel and webpack under the hood, but works with zero configuration.

When you’re ready to deploy to production, running npm run build will create an optimized build of your app in the build folder. You can learn more about Create React App from its README and the [User Guide] https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#table-of-contents.


