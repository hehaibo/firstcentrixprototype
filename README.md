# SK PROTECT first prototype

Live DEMO [here](https://jsuarez1992.github.io/firstcentrixprototype/).

## Quick start

The theme includes a custom Webpack file, which can be used to quickly recompile and minify theme assets while developing or for deployment. You'll need to install Node.js before using Webpack.

Once Node.js is installed, run npm install to install the rest of AdminKit's dependencies. All dependencies will be downloaded to the node_modules directory.

```sh
npm install
```

Now you're ready to modify the source files and generate new dist/ files. AdminKit is using webpack and webpack-dev-server to automatically detect file changes and start a local webserver at http://localhost:8080.

```sh
npm start
```

## Build tools

Start a local webserver at http://localhost:8080 and detect file changes:

```sh
npm start
```

Automatically detect file changes without starting a local webserver:

```sh
npm run watch
```

Compile, optimize, minify and uglify all source files to dist/:

```sh
npm run build
```

## Support

We are here to answer any questions you may have about AdminKit. Email us at support@adminkit.io and we'll respond as soon as we can.
