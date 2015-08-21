Marko Widgets with Lasso.js
===========================

This sample app demonstrates how to build a UI component using [Marko Widgets](https://github.com/marko-js/marko-widgets) that uses [Lasso.js](https://github.com/lasso-js/lasso) to bundle up the required JavaScript and CSS code.

# Installation

```
git clone https://github.com/marko-js-samples/widget-widgets-lasso.git
cd widget-widgets-lasso
npm install
```

# Running

You can choose to either run this application as a Express-based server or to simply build the static HTML, JS and CSS files.

## Option 1) Starting a Server

```
node server.js
```

Then visit: http://localhost:8080/

You can also use the [browser-refresh](https://github.com/patrick-steele-idem/browser-refresh) process launcher to automatically refresh pages any time a file changes as shown below:

```
npm install browser-refresh --global
browser-refresh server.js
```

To start in production mode (minification, bundling, fingerprinting, etc.) simply use the following command:

```
NODE_ENV=production node server.js
```

## Option 2) Build files only

```
node build.js
```

The generated HTML, JS and CSS files will be placed in the `build` directory in the root of the project.

To build static files in production mode (minification, bundling, fingerprinting, etc.) simply use the following command:

```
NODE_ENV=production node build.js
```
