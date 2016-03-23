# react-modal
Porting my Angular modal window module into React in order to learn React.

# Install Dependencies

- `npm install`

This will install both front and back-end packages.

### Install Global Dependencies

- `npm install -g nodemon postcss-cli-simple http-server browserify autoprefixer less concurrently`

These packages will be used via command line in the `package.json` build scripts so they should be installed globally.

# Building

- `npm run build` Shortcut command to build html, less, and javascript all at once

# Running

- `npm start` Runs the project at http://localhost:8080 using `http-server`

Additionally, in a new terminal tab, you can run a `watch` script as well:

- `npm run watch` Will run a watch script to rebuild after changes to html, less, and javascript files

# Additional Build scripts

- `npm run build-html` Builds and localizes html
- `npm run build-js` Runs Browserify and bundles javascript
- `npm run build-less` Runs less preprocessor, autoprefixer and bundles css
- `npm run copy-statics` Copies everything from /statics and puts it in /pub

Note: `npm run build` does all of the above at once
