# Text-Editor-PWA

## Description

This project is a text editor that runs in the browser, built as a Progressive Web Application (PWA). It features data persistence techniques using IndexedDB to ensure content is saved and retrieved even when offline. This application is a single-page application (SPA) and includes a service worker and a manifest file, making it installable on desktop.

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [License](#license)

## User Story

AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use


## Acceptance Criteria


GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client-server folder structure
WHEN I run npm run start from the root directory
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
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application


## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>

Install dependencies with npm install 

run the server with npm run start 

This will start up the backend and serve the client.
Open your browser and navigate to http://localhost:3000.
You can now create notes or code snippets, which will be saved in IndexedDB.
The application works offline and can be installed as a desktop application.

## Technologies Used
HTML
CSS
JavaScript (ES6+)
Webpack
Babel
IndexedDB (idb library)
Workbox
Express.js
Node.js

## License 

MIT license

## Credits 
to the teaching staff of Columbia University Coding Bootcamp
