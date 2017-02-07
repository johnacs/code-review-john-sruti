# Code Review for Sruti Keerti

## Project Repo

https://github.com/skeerti2/wdi-project-1-skeerti2

## Review

#### Project Purpose

This game is created as part of the WDI course fulfillment.

The project is based on "Wack-a-mole" gameplay with 2 game levels

| Component        | Filename           |
| ------------- |:-------------:|
| main instruction html  | index.html |
| game html page     | index2.html      |
| style sheet | style.css, style2.css   |
| javascripts | script.js, object_attempt.js   |

#### Project Organization

#### Features

* Time based game
  * using setInterval and clearInterval
* Animation
  * using animated gif. Uses addClass and removeClass to make gif appear
* Randomisation
  * function randomizeLevel1 using Math.random
* Has music
  * using <audio> tag and play()

#### Areas of Success (Code, Organization)

* Fun gameplay
* Nice use the use of color and animation
* Code is modular
* Good naming of variables and functions. Code is self explaining

#### Areas for Improvement (Code, Organization)

* Some repeated functions
  * maybe refactor randomizeLevel and updateTimeLevel
* At the end of game, a popup window appears. Should implement in the DOM
* Remove dupDuplicated jQuery link on index2.html
  * use only one jQuery link
* Google font duplicate link
  * duplicated links in style.css / index.html, style2.css/index2.html
* Unused js link "page1.js" on index.html


## Additional Notes
