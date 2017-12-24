# Speech Recognition in an Electron desktop app using annyang

use the [annyang API readme](https://github.com/TalAter/annyang/blob/master/docs/FAQ.md#why-does-speech-recognition-repeatedly-starts-and-stops) to debug this electron app. Right now speech recognition is starting and disconnecting, console.log()s not currently working, annyang code lives in index.html

**Clone and run for a quick way to see Electron in action.**

This is a minimal Electron application based on the Electron [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start), with some added Speech Recognition magic.

You can learn more about Speech Recognition on the [annyang page](https://github.com/TalAter/annyang).
This is a minimal Electron application based on the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start) within the Electron documentation.

**Use this app along with the [Electron API Demos](http://electron.atom.io/#get-started) app for API code examples to help you get started.**

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start).

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/TalAter/annyang-electron-demo.git
# Go into the repository
cd annyang-electron-demo
# Install dependencies and run the app
npm install && npm start
```