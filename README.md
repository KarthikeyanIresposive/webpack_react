
# webpack_react

 Initialize the project:

Initialize a new Node.js project by running 
```sh
npm init 
```
Install necessary dependencies:

```sh
  npm install react react-dom typescript @types/react @types/react-dom webpack webpack-cli webpack-dev-server html-webpack-plugin ts-loader css-loader style-loader sass-loader node-sass --save-dev
```


Configure TypeScript:
   Create a tsconfig.json file in the root of your project to configure TypeScript. 

To set up Webpack with TypeScript and React, including appropriate CSS/SCSS loaders and JSX bundlers,
  you need to create a webpack.config.js file with the necessary configurations. 
  
Create a webpack configuration file (webpack.config.js) in the root of your project:
    

Add scripts to your package.json to build and run your app:
```sh
   "scripts": {
  "start": "webpack serve --mode development",
  "build": "webpack --mode production"
}

```
start your development server with: npm start
And build the production-ready bundle with:npm run build









