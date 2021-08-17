# CRA: under the hood

learning what create-react-app is doing under the hood

### Package Dependencies
- Webpack: ["bundles all our files into one file"](https://webpack.js.org/)

- babel-loader: ["works with Webpack to transpile ES6+ into ES5 which is supported by older browsers"](https://www.npmjs.com/package/babel-loader)

- @babel/preset-react: ["extends Babel support to JSX"](https://babeljs.io/docs/en/babel-preset-react)

- html-webpack-plugin: ["simplifies the creation of HTML files to serve your Webpack bundles"](https://webpack.js.org/plugins/html-webpack-plugin/)

- webpack-dev-server: ["allows you to use Webpack with a development server that provides live reloading."](https://webpack.js.org/configuration/dev-server/)

- webpack-cli: ["webpack CLI provides a flexible set of commands for developers to increase speed when setting up a custom Webpack project."](https://www.npmjs.com/package/webpack-cli)

- css-loader: ["allows Webpack to convert the CSS file into a JavaScript string."](https://www.npmjs.com/package/css-loader)

- ["style-loader: inserts the JavaScript string into HTML dom."](https://webpack.js.org/loaders/style-loader/)

- @babel/plugin-proposal-class-properties: ["This plugin transforms static class properties as well as properties declared with the property initializer syntax"](https://www.npmjs.com/package/@babel/plugin-proposal-class-properties)

- react: ["React is a JavaScript library for creating user interfaces"](https://www.npmjs.com/package/react)

- react-dom: ["Serves as the entry point to the DOM and server renderers for React"](https://www.npmjs.com/package/react-dom)