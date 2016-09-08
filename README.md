# 360WebViewer
This project utilizes open source libraries to create a more immersive web
experience. The ultimate goal is to create a browser add-on that detects 360
degree content in web browsers and prompts the user to input using webcam gaze
tracking.

# How to Set up
This project requires two libraries to be placed in a folder in the root
directory titled "libs".

* Clone [this repo] (https://github.com/jsimonson2013/360WebViewer.git).
* Create a folder titled "libs" in the root directory.
* Go to [brown's webgazer library] (https://webgazer.cs.brown.edu/#download).
* Click the Download WebGazer.js button and save it (Ctrl + s) as "webgazer.js"
in the libs folder from step 2.
* Go to [mozilla's vr library] (https://aframe.io/docs/0.3.0/introduction/getting-started.html#include-the-js-build).
* Click the Development Version 0.3.0 button and save it as "aframe.js" in the
libs folder from step 2.

# Running the Project
Requirements

* Latest version of Firefox

To run the project simply navigate to the test.html file in a file explorer and
open the file with Firefox. Firefox should launch and prompt you to allow the
page to use your webcam. Allow the site to use your webcam and a window should
appear in the upper left corner of the window.

This may take a few attempts as the processes for rendering 3D content and eye
tracking a resource intensive and currently bug prone. 

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

# Libs
This directory is intended to hold all dependencies for the project. 

Currently there is no dependency management system so any additional libraries to be added
should be documented in the "How to Set up" instructions above.
