# PWA_text-editor

![GitHub](https://img.shields.io/badge/license-MIT-purple?style=plastic)

Render URL: 

## Description

This is a PWA text editor with both back-end and front-end components that render dynamically and store everything in a IndexedDB which can be accessed through the development tools (right-click & scroll to 'inspect' and click). JavaScript files are bundled using a webpack and generate an HTML file, service worker, and manifest file. PWA can be used offline due to cache data being saved and stored in the web browser.

## Installation

Open integrated terminal under the Main package.json file in VS code. Run "npm i" to install the dependencies in order to properly use the PWA, then run the command "npm run build" in order to build the application with the webpacks. Once complete, finally input "npm run start:dev" to deploy the PWA locally. Inside the dist folder open integrated terminal under index.html and right-click it to "Open Live Server" and display the text-editor.

Technologies Used:

- Node.js
- Workbox
- JavaScript
- HTML
- CSS
- MarkDown
- Express.js
- JSON
- IndexedDB

## Usage

If you don't want to import the repo code to your local device, you can use the Render URL to access the deployed PWA and install it onto your computer by clicking "Install" in the upper left hand corner. To use the text-editor simply click on the URL and start typing and press enter once done to jump down to the next line. All data will be stored in the IndexedDB, can even be accessed offline!

(Ex.) 

## Credits

UCSD GitLab modules for this assignment: Progressive Web Application

UCSD Xpert Learning Assistant A.I

Youtube: https://www.youtube.com/results?search_query=pwa+tutorial+for+beginners

Chrome Docs: https://developer.chrome.com/docs/workbox/modules/workbox-webpack-plugin#type-GenerateSWConfig

## License

Please refer to the LICENSE in the repo