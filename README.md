# Food Fight!

Group project (3 day timeline June 2016) to demonstrate knowledge learned during Nashville Software School's 6 month bootcamp front end curriculum. 
Single page application using jQuery to play a semi-random battle game. Food Fight theme, completely custom code.

Written with [Hannah Hall](https://github.com/hannahhall) and [Keith Bradley](https://github.com/keithbradley1). I wrote bonus.js, foodfight.js, and contributed heavily to app design and all javascript files especially animations. I also hand-drew all app images. 

deployed at [http://megancford.github.io/Food-Fight/](http://megancford.github.io/Food-Fight/)

---------
## Install 

```
$ git clone https://github.com/MeganCFord/Food-Fight.git
$ cd Food-Fight  
$ npm install
```
serve on local server of choice: http-server is an app dependency.

---------

### Exercise Requirements
Time to use protypal inheritance to build a game.

Some enterprising, young, software developer decided to build a simple web-based RPG that lets a human player fight against an array of different enemies. Unfortunately, there wasn't enough time to finish the project because aliens took over the Earth and everyone was shipped off to the plutonium mines.

Your job is to finish the game.

To do so, you need a firm understanding of prototypal inheritance. Start by examining the files `player.js`, `classes.js`, and `enemies.js` to see how the prototype chains were initially set up.

The game now belongs to you, intrepid adventurer. You can change the theme completely (aliens vs. undead, or axis vs. allies), style it however you want, but you need to have multiple classes, weapons, and enemies that the player can fight against.

Once the player has chosen all options for class, weapon, etc., you need to have a battlefield view that fulfills the following criteria.

1. Display the initial statistics for the player and the enemy.
2. Have a button with the label "Attack".
3. Each time the attack button is clicked, the player's chosen character and the generated enemy should attack with their weapon, and once the damage is calculated, subtract that from the opponents' health.
4. As soon as either combatant reaches health of 0, disable the attack button and annouce the winner.

-----------

#### License: [MIT](LICENSE.md)
