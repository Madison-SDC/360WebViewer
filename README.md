# 360WebViewer
This project utilizes open source libraries to create a more immersive web experience. This will be a website/webapp that showcases the immersive webviewing capabilities. The purpose of the website is to promote the browser add-on that we will create with this. The application will detect 360 degree content in web browsers and prompts the user to input using webcam gaze tracking. The panning of the 360 degree content will then be handled by gaze tracking, ie. if the user looks at the right edge of the 360 degree photo/video the photo/video will pan to the right. Hopefully this will provide a more immersive 360 degree content viewing on personal computers.

# How to Set up

* `git clone https://github.com/jsimonson2013/360WebViewer.git`
* `cd 360WebViewer`
* `npm install`

# Running the Project
Requirements

* Latest version of Firefox

To run the project simply navigate to the 360WebViewer directory and run

* `npm run dev`
* If Firefox is not your default browser you will have to open Firefox and paste the server address in the URL

# Layouts
This directory is intended to hold all html files.

test.html is a sample layout that shows how to include the correct scripts as
well as implementation of basic aframe components and a sample webgazer
application.

# Javascript
This directory is intended to hold all javascript files.

webgazerExample.js is taken from the script in brown's webgazer sample project.

# Styles
This directory is intended to hold all css files.

Currently, there is only a sample stylesheet for this application but a uniform
style would make the front end seem more professional.
