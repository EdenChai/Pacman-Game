# Pacman Game
### Overview
This is a pacman game for our web development course.<br>
We used JavaScript, jQuery, HTML and CSS.

## Created by
* Eden Chai - 206259848<br>
* Arie Katz - 209406164

## Link to game website
You can [click here](https://edenchai.github.io/Pacman-Game/) to play our game.

## Game Screens:
* **Home** - a page that contains a logo, Legister and Login buttons.
* **Register** - a page that allows the user to register to the site, using jquery validation to make sure the inputs are valid.
* **Login** - a page that allows the user to login, using jquery validation to make sure the inputs are valid.
* **Settings** - a page that asks the user to select preferences for the game, such as keys to play, number of food balls, number of ghosts, time of the game, colors for the food points. There is a random button that randomly changes the prefernces.
* **Game** - a page that has the game itself and at the top of the game it shows: the username, score, time passed from the game's beginning, and how many lives the user has. On the side, the user sees the preferences he has chosen and a new game button.

## Game Rules:
* Use the keys selected to move around the board.
* Eat food for score. There are 3 kinds of food points, smaller worth 5 points, medium worth 15 points and big worth 25 points.
* If a ghost catches the pacman, you lose 1 life and 10 points off the score.
* If you eat the special moving candy, you get 50 points.
* Game ends when:
    * Win: if pacman eats all the food on the board or time's up and the score is above 100 points.
    * Lose: if pacman loses all it's life (Loser) or time's up and the score is below 100 poins.

## Functionality Added:
We've added the following special functionality:
* We added a pill that upon pickup grants the player an additional life.
* We added a snowflake that upon pickup freezes the ghosts and makes those move slower for 10 seconds.
* We added a clock that upon pickup adds additional time to the timer and allows the player to have more time to finish the stage.
