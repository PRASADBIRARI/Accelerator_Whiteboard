# Accelerator
Free Online Conference and Collaboration Tool with build in WebRTC MCU/SFU running in NodeJS

![previmg](/public/images/acc.png)

### Available functions ###

- [x] Online Conferences with up to 6 participants per room (all Audio / Video)
- [x] Online Conferences with up to 250 participants per room (all Audio / only Moderator video)
- [x] Screenshare
- [x] PDF and HTML5 Presentations
- [x] Collaborative Whiteboard 
- [x] Youtube viewer
- [x] 3D Object viewer
- [x] User interactions with draggable items (like Textboxes, Drawings...)
- [x] Fileshare
- [x] Text Chat
- [x] Etherpad in IFrame (Must be hosted on its own)
- [x] much more...

### Installation without Docker ###
1. install nodeJs
2. run: npm install
3. run: node server.js
4. surf to: http://127.0.0.1:8080

Note: 
* To serve it online you need a reverse proxy and deliver with https (look at "Behind a reverse Proxy" below)
* On some linux systems you need to install some extra deps to run puppeteer

### Configuration ###
On the first start a new folder "/config" will be generated. Take a look at "/config/config.json" for all parameters. Change them if you like, and restart the server. If you don't see a config.json inside the /config folder set permitions of to mount:`chmod -R 777 /home/acc` and restart the container: `docker restart acc`.

More to come...

