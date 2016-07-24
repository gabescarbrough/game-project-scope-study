# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
    - [wireframes on GitHub](https://github.com/gabescarbrough/tic-tac-toe/tree/master/wireframes)
-   The data structure you plan to use.
    - I plan to use both objects and arrays. An object to represent the game board while in play (to more easily manipulate specific space values), and arrays to represent finished game boards to be sent to the backend.
-   How you will take the markup of the game board and represent it in JS
    - Each space on the board will have a unique ID which corresponds to a key in a Javascript object. Values will be either undefined, X and O. If a space is currently undefined it can be changed to an X or O (depending on turn), if it already X or O this is not allowed.
-   How you plan to approach this project.
    - I plan to follow the [suggested schedule](https://github.com/ga-wdi-boston/game-project/blob/master/schedule.md) as it makes perfect sense and I'm a sucker for following directions.
-   4-8 user stories for your game project.
    - [user stories on GitHub](https://github.com/gabescarbrough/tic-tac-toe/tree/master/user-stories)
-   How you plan to keep your code modular.
    - I plan to keep my code modular by separating functions into files based on the Model-View-Controller architecture. The model is the board represented as a Javascript object. The view is the HTML/CSS gameboard the user sees, and the controller is the functions that take the users clicks and use them to manipulate the JS object that represents the gameboard. There will also be functions for communicating with the API which will be grouped separately. These create an array of board values from the gameboard object to be sent to the back-end (as that is the datatype it expects) within a object representing the game, as well as get game information from the backend to display wins and losses. Game logic functions will be grouped together as well.
-   What creative spin will you add to your project.
    - My project will utilize different views and clean minimal design to create an enjoyable experience.
-   How you will use version control to backup / track your project.
    - I will commit anytime I make changes that lead to a new working state.
-   Do you plan to attempt any of the bonuses.
    - I plan to attempt keeping track of multiple game rounds with a win counter, get creative with styling, and use localStorage.
