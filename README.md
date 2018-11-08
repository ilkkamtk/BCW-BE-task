# Basic Concepts of Web Applications - Back end task

How to run:

`npm install`

`npm run watch` or `node server.js`

Open localhost:3000 in browser

## Make a backend to the app in this repo

App features:
  * Add a form to upload data and image
  * First set the coordinates with two input fields in the form. Later you can do it by clicking (Leaflet etc.) map or get the coordinates from EXIF data.
    * [EXIF](https://github.com/gomfunkel/node-exif)
  * Upload image
    * send as [FormData](https://developer.mozilla.org/en-US/docs/Web/API/FormData)
    * receive with [_multer_](https://github.com/expressjs/multer)
  * Convert image to small and medium versions
    * [_sharp_](https://github.com/lovell/sharp)
  * Save the data from the form and image urls to database
  * Display the updated data on the frontend