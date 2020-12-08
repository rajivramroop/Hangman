HANGMAN GAME
README
\\
The design includes a start game screen with a photo of the hangman. Once it is clicked, the game begins.

The idea is very simple. We created 5 "x" characters on the screen that represent trials, as one would have in a hangman game (in place of adding a hangman animation). Every time a user enters a word wrong, we implemented a function to decrement the "x"'s. We used an input stream method to add a file containing all of the words we chose.  In the main game functionality, these words would be shuffled and one of the words would be chosen as the word the user would receive. That word is stored in a variable gets revealed once the user wins the game. If the user loses the game, the word will not be displayed, and it returns to the start screen.

The amount of tries left corresponded with another variable, and was proportional to the amount of X's displayed on the screen. There were also several checks used to test user input, with basic if statements to add words to fill up initialized blanks on the screen.

When the user guesses all the words, the game ends, displaying "You Win!"

There is also a reset button that can be used to begin the game all over again. To implement this, we used an onClick function that can be seen in both the xml and mainactivity files. 
