# mediaLab5

This lab aims to build video streaming app based on WebRTC framework.

Some good examples:
https://www.scaledrone.com/blog/webrtc-tutorial-simple-video-chat/

# Place all laboratory on the github.io.
  - ROOT folder should contain 5 folders (lab1, lab2, lab3, lab4 & lab5) and index.html.
  - index.html should have links to each folder.
  - Each folder should be prepared to load solution.

# Requirements for repository
  - You have to clone this repository and make two branches (master and develop).
  - The develop branch should contain commits of every new feature of the AR application.
  - When all features will be ready you have to merge the development branch to the master.

# Requirements for streaming application
There are two options to choose from. 

Option A:
  - Capture images from camera by using WebRTC API. Basic code for chat application is provided.
  <!--COMPLETED:-->
  With the server running, open a recent version of Firefox, Chrome, or Safari and visit `https://localhost:8443`.
  - By using RTCPeerConnection send images from camera to the client and display them.
  <!--COMPLETED:-->
  - You can use base64 to encode image to string and decode on client side.
  <!--COMPLETED:-->
  Every ws method is explained in the node_modules/ws/lib/package.json.
  With the use of these functions I believe we stream video by encoding images it to base32 and sending it to the client & vice versa.

To fully launch this application one needs node.js and npm installed
then to just in the (while being in the node.js folder) cmd write:
-npm install
-npm start
  
Option B:
  - Find out how WebRTC API is designed.
  - Create client and server pages.
  - Server page should capture video from browser.
  - Client page should display stream. 
  
  
The general requirements for option A & B.
  - Test application on at least two browsers and specify in README.md which version and browser it was.
  - To pass this lab, you have to fully complete an option.  