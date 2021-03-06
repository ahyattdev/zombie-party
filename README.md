# Zombie Party
A top-down arcade zombie shooter written with the HTML5/JavaScript Phaser game library.

You can play this game at https://ahyattdev.github.io/zombie-party/

Welcome to Zombie Party!

It is recommended that this game is run on Chrome 49 or later. 

This game uses Phaser 2.4.3 and is untested with newer versions. 

For the code that makes up the actual game, please look in js/play.js. 

The game levels are edited with a program called Tiled. 

The textures seen in the game are in assets/sprites/tileset.png. 

## Project Layout

```
├── README                  This file
├── assets                  Where game assets are stored
│   ├── levels              Where the game levels are stored
│   │   ├── level-1.json
│   │   ├── level-10.json
│   │   ├── level-2.json
│   │   ├── level-3.json
│   │   ├── level-4.json
│   │   ├── level-5.json
│   │   ├── level-6.json
│   │   ├── level-7.json
│   │   ├── level-8.json
│   │   └── level-9.json
│   ├── sounds              Where the game sounds are stored
│   │   ├── clipempty.mp3
│   │   ├── itempickup.mp3
│   │   ├── laser.mp3
│   │   ├── playerdie.mp3
│   │   ├── reload.mp3
│   │   ├── teleport.mp3
│   │   └── zombiedie.mp3
│   └── sprites             Where the game images are stored
│       ├── background.png
│       ├── bullet.png
│       ├── eastbutton.png
│       ├── logo.png
│       ├── martin.png
│       ├── mute.png
│       ├── northbutton.png
│       ├── southbutton.png
│       ├── tileset.png
│       ├── westbutton.png
│       └── zombie.png
├── index.html              Used to load this webapp
├── js                      Where the JS files are stored
│   ├── end.js              The game state for when the player dies
│   ├── load.js             Responsible for loading game assets
│   ├── menu.js             Presents the main menu
│   ├── play.js             The actual game
│   ├── selectlevel.js      Where you choose a level to play
│   └── zombieparty.js      Initiates the game
├── phaser.js               The library this game uses
├── phaser.map              Used for debugging
├── phaser.min.js           A minified version for faster JIT compilation
└── stylesheet.css          A minimal CSS stylesheet
```
