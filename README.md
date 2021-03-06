Create-react-app template with Sass builder and custom Babel configuration options.

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

You almost never need to update `create-react-app` itself: it delegates all the setup to `react-scripts`.

PS. Add this to your .bash_aliases or .bash_profile to be able to run locally installed npm executables with npm-do.
`function npm-do { (PATH=$(npm bin):$PATH; eval $@;) }`

## Babel config

Edit config-overrides.js to suit your needs.

## Available Scripts

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

### `npm run build-css`

Build src/*.scss files. (Included in npm start and npm run build)

### `npm run watch-css`

Build src/*.scss files automatically on save. (Included in npm start and npm run build)

### `npm run start-js`

Used in building Sass and running dev-server.