# Vaadin Elements App

### Intro

This is a [Payment Request API](https://www.w3.org/TR/payment-request/) demo app built with
[Vaadin components](https://vaadin.com/components) and [Polymer](https://www.polymer-project.org).

### [Online demo](https://jonni.app.fi/payment-demo/)

### Setup

##### Prerequisites

Ensure npm, bower and polymer-cli are installed

 * [npm installation instructions](https://docs.npmjs.com/getting-started/installing-node)

 * $ `npm install -g bower polymer-cli`

### Start the development server

This command serves the app at `http://localhost:8080`

$ `polymer serve`

### Build

This command builds your Polymer application for production and generates service worker, using build configuration options provided by the command line or in your project's `polymer.json` file.

You can configure your `polymer.json` file to create multiple builds. You can define your own named builds, or use presets. See the Polymer's documentation on [building your project for production](https://www.polymer-project.org/2.0/toolbox/build-for-production) for more information.

$ `polymer build`
