# Number Guessing Game

**Main Code:**
- https://github.com/aln-aimna/number_guessing_game/blob/main/NumberGuessingGame.ipynb

**Supporting Files:**
- https://github.com/aln-aimna/number_guessing_game/blob/main/higher.gif
- https://github.com/aln-aimna/number_guessing_game/blob/main/lower.gif
- https://github.com/aln-aimna/number_guessing_game/blob/main/congrats.gif

## What the Program Does
This is a Number Guessing Game developed in Python Jupyter Notebook. The user attempts to guess a randomly generated number. The user will be asked to choose a difficulty level at the start. The game validates user input, provides hints when the guess is high or low, and allows the user to decide whether to continue or not each game.

## How to Run
Open NumberGuessingGame.ipynb in Jupyter Notebook or VS Code. Make sure the supporting files higher.gif, lower.gif, and congrats.gif are in the same folder as the notebook. Run all cells in order, then run:

start_game()

or click Run All

The game expects a difficulty level selection (1, 2, or 3), followed by number guesses within the selected range.

## Debugging Challenge
Although its normal for developers to encounter error during testing but my main challenge was understanding how interactive input works in VS Code. At first, I thought the program had frozen because I could not see where to enter my input. I later realized that VS Code's Jupyter interface displays the input prompt differently from the Jupyter Notebook.

I also encountered errors after restarting the kernel or cancelling an active input. I learned that restarting the kernel clears the current Python state, so the functions need to be executed again before start_game() can use. This helped me understand the difference between writing a function and actually loading it into the current kernel session.
