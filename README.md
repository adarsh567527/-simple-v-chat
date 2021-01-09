# Simple WebRTC Messenger

A tutorial on building a WebRTC video chat app with [SimpleWebRTC](https://simplewebrtc.com/) , that allows you to communicate with (for example) your customers in real-time.

Article URL: [http://www.sitepoint.com/webrtc-video-chat-application-peerjs](http://www.sitepoint.com/webrtc-video-chat-application-peerjs)

## Requirements

* [Node.js](http://nodejs.org/) Environment
* An account with [now.sh](https://zeit.co/now)

## Installation Steps

1. Clone repository
2. Run `npm install`
3. Start the server with `npm start` or `node server`
4. Visit [http://localhost:3000/](http://localhost:3000/)

HTTPS is required for remote cameras and remote microphone to work. Currently, there's no known method for creating SSL certificates for a private IP address. You can easily acquire a free SSL certificate for a public domain.

## Deployment Steps

If you would like to quickly test out the app on a public domain without dealing with the hassles of setting up SSL, simply deploy they app with [now.sh](https://zeit.co/now)

1. Clone repository
2. Run `npm install`
3. Run `npm install -g now`
4. Deploy the server with `now --public`. Follow the printed out instructions
5. Visit the url provided
6. Enter room name and username, click 'Create Room'
7. Invite a friend or use another device with a front camera, visit the url. Give another name but provide the same room name
8. Remote videos should show up on both videos. You can also send chat which also works without video

If the video stutters or freezes, it's probably due to the slow upload speeds given by your ISP.

