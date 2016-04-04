# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss on Monday morning.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
    https://moqups.com/#!/edit/louarnos/2LA4KLz5

-   The data structure you plan to use.

    makeMove() - sets the board a mark on the board based on a players move.
                 Will use Jquery for DOM manipulation.

    findWin() - iterates over the board and returns boolean for a win.
                If Win is found will use DOM manipulation.

    resetGame() - resets board.
                  Initializes new game, resetting the board{}

    board{} - array of arrays
              Use string x's and o's to mark different indicies.

    player{} - object with key value pairs

    game{} - contains player and board objects

-   How you will take the markup of the game board and represent it in JS

    I was considering using <canvas> or a table, but I think I am going to just
    use divs for the game board, and either text/pictures/icons as the x's and o's.

    I plan to use an array of arrays to represent the game board. It will look
    something like:

    let board = [[null,null, 'x'],
                [null, 'x', null],
                ['x', null, null]]

-   How you plan to approach this project.

    I plan to create a rough but functional version of my front end, and
    then move onto my javascript. While I create my objects and functions I will
    insert my Jquery code, to be sure I have a firm grasp on how my JS will interact
    with my markup. I may opt to store game data in my javascript
    objects intially until I get the JS operating the way I want, and then move on
    to working on my AJAX calls, and storing data on the backend. Once everything
    works, files are organized well, the code is readable, and it meets the requirements
    of the project I will then focus of making it look good.

-   4-8 user stories for your game project.

    As a user I want to be able to customize my icon I use to mark the board so
    that I identify with the game.

    As a user I want to be able to have my username show up on the score board so
    that the game feels personalized.

    As a user I want to be able to determine the size of the game to change the
    game up some and to keep things interesting.

    As a user I want to be able to see my total number of wins and losses,
    against this opponent and in general  to see my progress in the game.

-   How you plan to keep your code moodular.

    I would like to have seperate files for my HTML, css, JS (ideally) jquery, and ajax.
    I think my login AJAX methods and my AJAX methods for storing game data will
    be in seperate files to make them more usable in the future.

-   What creative spin will you add to your project.

    I would like to make it so that the user can set the size of the board at
    the beginning of the round, which would also make it so that number of x's
    or o's needed would increase. I'd like to stylize it quite a bit, time permitting.

-   How you will use version control to backup / track your project.

    Using github, I'll have seperate branches for my hmtl/css, js, and ajax. When
    I being to work on a big portion of one of these, say the findWin() function
    in JS, I will create a branch off of my JS branch.

-   Do you plan to attempt any of the bonuses.

    I'd like to implement them all, but I'm not sure this is realistic given
    the amount of time. I think the icons and keeping track of a score are the
    easiest to implement. Integrating chat and allowing people to play on multiple
    devices really interest me as well, but seem to be more ambitious.
