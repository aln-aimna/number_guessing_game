# Number Guessing Game
## What the Program Does**
**Main Code:**
- https://github.com/aln-aimna/number_guessing_game/blob/main/NumberGuessingGame.ipynb

**Other needed files:**
- https://github.com/aln-aimna/number_guessing_game/blob/main/higher.gif
- https://github.com/aln-aimna/number_guessing_game/blob/main/lower.gif
- https://github.com/aln-aimna/number_guessing_game/blob/main/congrats.gif

The Number Guessing Game generates a random number between 1 and 10 and asks the user to guess it. After each guess, the program gives a hint by telling the user to guess higher or lower until the correct number is found.

## How to Run

Open the .ipynb file in Visual Studio Code with the Jupyter extension installed. Run the notebook cells from top to bottom, then run the final cell containing:

guess_number()

The program expects a whole number between 1 and 10 as input. If the user enters something that is not a valid number, the program displays an error message and asks for another input.

## Debugging Challenge

One challenge I encountered was handling invalid user input. The input() function returns a string, so I needed to convert the user's input into an integer before comparing it with the randomly generated number. When the input could not be converted to an integer, Python raised a ValueError. I read the error and realized that I needed to handle invalid input using try and except. I added a try block around the integer conversion and used except ValueError to display a message and ask the user to enter a valid number again.
