Tic-Tac-Toe game with a move history, to jump to different history point.

# How to run locally?
* Install Node.js
* `npm i`
* `npm run start`
  * Problems: "Unexpected token for <>"
    * Attempt1: Adding `<script src="js/reactjs/main.js" type = "text/babel"></script>`
      * see [here](https://stackoverflow.com/questions/20905227/reactjs-unexpected-token-error)
    * Attempt2: Adding `<script type="text/jsx">`
    * Attempt3: `npm install babel-preset-react`
    * Attempt4: `/** @jsx React.DOM */` at top of your files
    * Solution: ❓It already works

# How was created?

* bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app)

## Folder Structure


```
my-app/
  README.md
  node_modules/
  package.json
  public/
    index.html
    favicon.ico
  src/
    App.css
    App.js
    App.test.js
    index.css
    index.js
    logo.svg
```

* files / MUST exist with these concrete names
  * `public/`
    * `public/index.html`
      * ONLY can use files | `public`
    * NOT included -- for -- production
  * `src/index.js`
    * == JS entry point

* other files
  * can be delete or rename 

* `src/`
  * subdirectories can be created
    * Reason: 🧠 faster rebuilds 🧠
  * 👀by default, ONLY files / processed by Webpack 👀

## Dependencies
* `react-scripts`
  * scripts command / make easier to build React applications
  * see [here](https://github.com/facebook/create-react-app/tree/main/packages/react-scripts)
