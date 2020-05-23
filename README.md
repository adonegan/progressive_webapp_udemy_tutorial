# Introduction

This is from Udemy's Learn to Build Progressive Web Apps using Javascript course. It is for testing purposes only.

## Setup

1. Install [Node.js]('https://nodejs.org/en/download/')

2. Install http-server using npm

## VSCode

- Add index.html page with boilerplate, include input and button
- Add main.css file to style input and button
- Add main.js file, create empty list use interpolation as placeholders for api information requests, add async function
- In main.js, add fetch from [JSONPlaceholder]('http://jsonplaceholder.typicode.com/')
- Create manifest.json to specify webpage details
- Use http-server -p 8080 -a localhost -c 0 to create localhost in browser

## Chrome Dev Tools

When html displays in browser, press View > Dev Tools > Inspect and go to Applications. See your manifest informtion and Cache Storage to check if manifest.json and main.js specifications have worked.
