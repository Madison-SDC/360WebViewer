# 360WebViewer

This project utilizes two open source libraries to create a virtual reality experience on laptop and desktops computers. WebGazer.js (https://webgazer.cs.brown.edu/) uses computer vision to track user gaze with builtin webcams. AFrame (https://aframe.io/) allows easy creation of 360-degree scenes and components for interacting with 360 element. A custom JavaScript Event is fired when user gaze moves and a custom look-control responds by panning accordingly. 

Because this project requires the webcam, web browsers require it to be hosted on HTTPS. However, this can be worked around using the Google Chrome flag: --unsafely-treat-insecure-origin-as-secure. Instructions for setting up the project and running it can be found below.

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
* Open Chrome and navigate to copied url address
