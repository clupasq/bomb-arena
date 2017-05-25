# bomb-arena
An HTML5 multiplayer arena-style combat game made with Phaser and socket.io.
Play it at:

- https://limitless-brook-9339.herokuapp.com/ (original server)
- https://bomb-arena.glitch.me/

###How to run locally
Make sure you have NodeJS installed on your computer.

Go to client/src/main.js and comment out the first line in the startGame function (the code connecting to Heroku). Uncomment the line that connects to localhost:8000. 

Navigate to the project root.

```
$ npm install
$ node server/server.js
```

Open up your browser and navigate to localhost:8000/index.html.

###Technologies/tools used:
- Phaser
- Socket.io
- Node
- Heroku
- Gulp
- Browserify/Watchify
- Photoshop
- Tiled
- TexturePacker
