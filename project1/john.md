# Code Review for John

## Project Repo

https://github.com/johnacs/wdi-project-1-johnacs

## Review

#### Project Purpose

The project is inspired from the game app Infinity Loop and aims to implement 7 levels of the same. The game is implemented using the concepts of HTML5, CSS, jQuery, JavaScript and is organized into the following files:

CSS         : reset.css, style.css

HTML        : index.html

JavaScript  : code.js
#### Project Organization

#### Features

* Animation
  * Clicking on the graphic element rotates it by 90 degree clockwise. This is achieved with the help of CSS Animation.  
* Level-based game
  * The start positions for each level are hard coded in the code.js file. The player moves are recorded and compared against a solution Array for each level.
* play Array update
  * A good technique of updating the play Array using deepClone() in order to prevent game elements (graphic elements) from being overwritten while game/level is played.

#### Areas of Success (Code, Organization)

* Pipe Animation on click
  * Clicking on the pipe element makes it rotate by 90 degree. This transition is very smooth and visually appealing.
* Code is well organized
  * Logic is implemented in modular functions and is very neat. No repetition of logic.
* README.md
  * Very well documented README.md file which includes explanation and game mechanics for each level. Reflects methodical implementation of project. YouTube video for game is also included.

#### Areas for Improvement (Code, Organization)

* The location of pipes for each game.
  * Every time the player plays the game, for each level, the start position of the pipes (including the rotation angle) remains unchanged. This way, a player can memorize his/her moves to win. The game can be further improved by shuffling start position/rotation angles of pipes to make it more exciting if player plays again.
* Comments in code
  * Maybe more comments can be added to make it easier to understand the flow of the logic/code.
