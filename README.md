# webpack_react
1.Initialize the project:

2.Initialize a new Node.js project by running npm init in the project folder. Follow the prompts to set up your package.json file.

3.Install necessary dependencies:
Install the required dependencies for a basic React with TypeScript setup:
  npm install react react-dom
  npm install typescript @types/react @types/react-dom

4.Configure TypeScript:
   Create a tsconfig.json file in the root of your project to configure TypeScript. 

5.To set up Webpack with TypeScript and React, including appropriate CSS/SCSS loaders and JSX bundlers,
  you need to create a webpack.config.js file with the necessary configurations. 
    npm install webpack webpack-cli webpack-dev-server html-webpack-plugin ts-loader css-loader style-loader sass-loader node-sass --save-dev

6.Create a webpack configuration file (webpack.config.js) in the root of your project:
    

7.Add scripts to your package.json to build and run your app:
   "scripts": {
  "start": "webpack serve --mode development",
  "build": "webpack --mode production"
}

8. start your development server with: npm start
9. And build the production-ready bundle with:npm run build

