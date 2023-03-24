# Text Editor

## Description
description

## Table of Contents

- [Built With](#built-with)
- [Installation](#installation)
- [Usage](#usage)
- [Preview](#preview)
- [License](#license)

## Built With

- Node.js
- Express.js
- PWA
- Service Worker
- Webpack

## Installation

- Install the required packages via `npm i` on the terminal of the root directory
- `npm run start` to build and start the application

## Usage

- AS A developer
- I WANT to create notes or code snippets with or without an internet connection
- SO THAT I can reliably retrieve them for later use

- GIVEN a text editor web application
- WHEN I open my application in my editor
- THEN I should see a client server folder structure
- WHEN I run `npm run start` from the root directory
- THEN I find that my application should start up the backend and serve the client
- WHEN I run the text editor application from my terminal
- THEN I find that my JavaScript files have been bundled using webpack
- WHEN I run my webpack plugins
- THEN I find that I have a generated HTML file, service worker, and a manifest file
- WHEN I use next-gen JavaScript in my application
- THEN I find that the text editor still functions in the browser without errors
- WHEN I open the text editor
- THEN I find that IndexedDB has immediately created a database storage
- WHEN I enter content and subsequently click off of the DOM window
- HEN I find that the content in the text editor has been saved with IndexedDB
- WHEN I reopen the text editor after closing it
- THEN I find that the content in the text editor has been retrieved from our IndexedDB
- WHEN I click on the Install button
- THEN I download my web application as an icon on my desktop
- WHEN I load my web application
- THEN I should have a registered service worker using workbox
- WHEN I register a service worker
- THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
- WHEN I deploy to Heroku
- THEN I should have proper build scripts for a webpack application

## Preview

Application
![image](https://user-images.githubusercontent.com/117130907/227539827-2ec6668b-1f57-45fe-90ea-e64a0aac5fa4.png)

Service Worker
![image](https://user-images.githubusercontent.com/117130907/227540926-e4b3d292-fac5-4cdc-974f-682398b18fa1.png)

Manifest
![image](https://user-images.githubusercontent.com/117130907/227541133-7ed880db-0878-4cdb-a51c-597a37b4aa95.png)

Local Storage
![image](https://user-images.githubusercontent.com/117130907/227541281-ba52f9e3-f5c5-4f30-a28c-2f3e296db449.png)

Offline 
![image](https://user-images.githubusercontent.com/117130907/227541401-7e7e16a3-2f8a-4b3c-a71c-93b1ad177bdf.png)

PWA
![image](https://user-images.githubusercontent.com/117130907/227541657-46e92584-7514-41ae-b60e-6082408a5e03.png)

## Deployed Application

https://peaceful-beach-14165.herokuapp.com/

## License

See LICENSE in repo
