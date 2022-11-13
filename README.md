# pwa-text-editor

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) ![Node.js](https://img.shields.io/badge/node-js-green) ![express](https://img.shields.io/badge/express-4.18.1-orange)

This project is a Progressive Web Application (PWA) text editor. It is a single-page application that runs in the browser. 

It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

Methods such as getting and storing data to an IndexedDB database has been implemented. I have also used idb package, which is a lightweight wrapper around the IndexedDB API.

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

# Screenshots of Application:

* Deployed Heroku Application:

![Deployed Heroku Application](./assets/images/heroku.png)

* Install Application Prompt:

![Install Application Prompt](./assets/images/install.png)

* Installed Application (can be used offline):

![Installed Application](./assets/images/installed-app.png)

# Link to Deployed Application:

[Click here](https://floating-gorge-81885.herokuapp.com/)

### Final note:

_Any feedback to improve code or implement best practice would be appreciated_ 😊