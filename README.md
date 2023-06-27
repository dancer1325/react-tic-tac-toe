Tic-Tac-Toe game with a move history, to jump to different history point.

# How to run locally?
* Install Node.js
* `npm i`
* `npm run start`
  * Problems: "Unexpected token for <>"
    * Attempt1: Adding `<script src="js/reactjs/main.js" type = "text/babel"></script>`. Check [here](https://stackoverflow.com/questions/20905227/reactjs-unexpected-token-error)
    * Attempt2: Adding `<script type="text/jsx">`
    * Attempt3: `npm install babel-preset-react`
    * Attempt4: `/** @jsx React.DOM */` at top of your files
    * Solution: ❓


# Notes

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

## Folder Structure

After creation, your project should look like this:

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

For the project to build, **these files must exist with exact filenames**:

* `public/index.html` is the page template;
* `src/index.js` is the JavaScript entry point.

You can delete or rename the other files.

You may create subdirectories inside `src`. For faster rebuilds, only files inside `src` are processed by Webpack.<br>
You need to **put any JS and CSS files inside `src`**, or Webpack won’t see them.

Only files inside `public` can be used from `public/index.html`.<br>
Read instructions below for using assets from JavaScript and HTML.

You can, however, create more top-level directories.<br>
They will not be included in the production build so you can use them for things like documentation.

## Dependencies
* `react-scripts`
  * Scripts command to make easier life to build React applications. Check [here](https://github.com/facebook/create-react-app/tree/main/packages/react-scripts)
