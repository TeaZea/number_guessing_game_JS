# number_guessing_game_JS

## A number guessing game made with JavaScript. To play, open node.js live-server npm on the index file, or live server extention from VSCode.

I was given the HTML and CSS. I was tasked with creating all the javascript to make the game interactive.

I used Math.trunc to create a random number between 1 and 20 and assigned it to a variable. I also created a starting score that would change depending on how many guesses the user made, and an empty highscore variable that would hold the users latest highscore once they've guessed the correct number.

Then I created the check guess button, where I used the eventListener 'click' to check the users guess against the randomly generated number.

As the user guesses, text on the page would change to give the users hints as a script checked if the guess was higher or lower than the randomised variable.

Upon a correct guess, the number would be shown on an enlarged area, the background would change, text would change to congradulate the user and the highscore would update if it was a higher score than the last game.

'Play again' button would also use the eventListener: 'click', to reset all the elements back to their original states and also randomize the seceretNumber veriable to a new number.
