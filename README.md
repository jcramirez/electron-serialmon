# electron-serialmon
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

Simple and basic serial monitor app built with electron, Node-Serialport, Bootstrap and Vue.js

Many thanks to [@johnny-five-io](https://github.com/johnny-five-io). This project was based the [electron-serialport](https://github.com/johnny-five-io/electron-serialport) project


**Clone and run for a quick way to see Electron and Serialport in action.**


**Use this app along with the [Electron API Demos](http://electron.atom.io/#get-started) app for API code examples to help you get started.**

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.
- `renderer.js` - Responsible for running the user-interface of your app.

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start).

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/jcramirez/electron-serialmon.git
# Go into the repository
cd electron-serialmon
# Install dependencies
npm install
# Run the app
npm start
```

### To build native Mac or Windows apps run the following command:

```bash
npm run-script packager
```

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/).

## Other Example Apps

For more example apps, see the
[list of boilerplates](http://electron.atom.io/community/#boilerplates)
created by the awesome electron community.

#### License [CC0 1.0 (Public Domain)](LICENSE.md)
