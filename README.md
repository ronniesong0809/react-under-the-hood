learning what create-react-app is doing under the hood

### Package Dependencies
- Webpack: bundles all our files into one file

- babel-loader: works with Webpack to transpile ES6+ into ES5 which is supported by older browsers

- @babel/preset-react: extends Babel support to JSX

- html-webpack-plugin: [“simplifies the creation of HTML files to serve your Webpack bundles”](https://webpack.js.org/plugins/html-webpack-plugin/)

- webpack-dev-server: allows you to use Webpack with a development server that provides live reloading.

- webpack-cli: [“webpack CLI provides a flexible set of commands for developers to increase speed when setting up a custom Webpack project.”](https://www.npmjs.com/package/webpack-cli)

- css-loader: allows Webpack to convert the CSS file into a JavaScript string.

- style-loader: inserts the JavaScript string into HTML dom.

- @babel/plugin-proposal-class-properties: [“This plugin transforms static class properties as well as properties declared with the property initializer syntax”](https://www.npmjs.com/package/@babel/plugin-proposal-class-properties)

- react: JavaScript library

- react-dom: [“Serves as the entry point to the DOM and server renderers for React”](https://www.npmjs.com/package/react-dom)