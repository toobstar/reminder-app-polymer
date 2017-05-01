# Simple Reminder App using Polymer Framework

### Start the development server

This command serves the app at `http://localhost:8080` and provides basic URL
routing for the app:

    polymer serve --open

### Build

This command performs HTML, CSS, and JS minification on the application
dependencies, and generates a service-worker.js file with code to pre-cache the
dependencies based on the entrypoint and fragments specified in `polymer.json`.
The minified files are output to the `build/default` folder.

    polymer build

### Hosting

Example hosted at Firebase

    https://reminder-2208a.firebaseapp.com

To update Firebase deployment run target

    firebase deploy
