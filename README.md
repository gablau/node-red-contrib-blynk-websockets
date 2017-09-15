---
### This project has been moved to  [node-red-contrib-blynk-ws](https://github.com/gablau/node-red-contrib-blynk-ws)
### [![NPM](https://nodei.co/npm/node-red-contrib-blynk-ws.png?mini=true)](https://npmjs.org/package/node-red-contrib-blynk-ws) [![npm version](https://badge.fury.io/js/node-red-contrib-blynk-ws.svg)](https://badge.fury.io/js/node-red-contrib-blynk-ws)
---
#
#
#
#
# node-red-contrib-blynk-websockets
Blynk app integration with Node Red using WebSockets protocol

## Websockets version
This works for both local and cloud Blynk servers.
For local, wss:// works if you ve got a certificate installed on Blynk server.
For cloud Blynk server, you can use ws://blynk-cloud.com:8080/websockets or wss://blynk-cloud.com:9443/websockets as the server url.

[![NPM](https://nodei.co/npm/node-red-contrib-blynk-websockets.png?mini=true)](https://npmjs.org/package/node-red-contrib-blynk-websockets)
[![npm version](https://badge.fury.io/js/node-red-contrib-blynk-websockets.svg)](https://badge.fury.io/js/node-red-contrib-blynk-websockets)

If you installed Node Red globally use this to install
```npm install --global node-red-contrib-blynk-websockets```

Supports both SSL wss:// and non secured ws:// connection to local server and cloud Blynk server.

### Supported events and widgets

- read event
- write event
- app event
- write command
- set property
- emails
- notify
- LCD widget

### Blynk App Settings

Use Raspberry PI as hardware to access 128 virtual pins or Generic Board for 32.

### How to use

See help of every nodes

### Debug

Use the verbose `-v` flag when starting Node-Red to get more information
or use node-red-log and enable log on Configuration Node as needed

### Available Nodes

TO ADD
