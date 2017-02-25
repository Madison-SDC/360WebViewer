# 360WebViewer
This project utilizes open source libraries to create a more immersive web experience. This will be a website/webapp that showcases the immersive webviewing capabilities. The purpose of the website is to promote the browser add-on that we will create with this. The application will detect 360 degree content in web browsers and prompts the user to input using webcam gaze tracking. The panning of the 360 degree content will then be handled by gaze tracking, ie. if the user looks at the right edge of the 360 degree photo/video the photo/video will pan to the right. Hopefully this will provide a more immersive 360 degree content viewing on personal computers.

# Software Requirements

* Node.js - https://nodejs.org/en/
* npm - (shipped with Node.js)
* Google Chrome - https://www.google.com/intl/en/chrome/browser/desktop/index.html (properties need to be modified, so it is wise to not use your standard Chrome install).

# How to Set up

* `git clone https://github.com/jsimonson2013/360WebViewer.git 360WebViewer`
* `cd 360WebViewer`
* `npm install`

# Running the Project

* `npm run dev`
* Copy the url address written to the output.
* Modify Google Chrome -Shortcut -Target Field properties to read: "/chrome-app-path/" --unsafely-treat-insecure-origin-as-secure="url-address-copied" --user-data-dir=/chrome-app-directory/
* Apply changes
* Navigate to copied url address

