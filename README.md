# video-conference-webrtc
Complete client/server application demonstrating how to setup a video conference with multiple peers using WebRTC.

## What the app does
This sample code demonstrates a client/server architecture running on <a href="https://nodejs.org" target="_blank">Node.js</a> that enables users to setup up a video conference. The app also uses 
<a href="http://socket.io" target="_blank">Socket.IO</a> and <a href="http://www.webrtc.org" target="_blank">WebRTC</a>.

The app generates a new room when a peer visits <a href="http://127.0.0.1:1337/" target="_blank">http://127.0.0.1:1337/</a>, which can then be used to invite others to the video conference.

<a href="http://www.foobubble.com" target="_blank">Demo</a>

<img src="https://cloud.githubusercontent.com/assets/10542894/7550897/538ec66a-f674-11e4-9f52-b0f5a5b9911d.png" width="450"/>

## How to run the code
1. Clone the repo: `$ git clone https://github.com/lucaslouca/video-conference-webrtc.git` 
2. `$ cd video-conference-webrtc `
3. `$ npm install` (you may need root access)
4. `$ node server.js`
5. Access the app from a WebRTC capable webbrowser through <a href="http://127.0.0.1:1337/" target="_blank">http://127.0.0.1:1337/</a>
