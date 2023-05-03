# Tic-Tac-Toe

A simple implementation of the ***"Tic Tac Toe"*** game made with love and passion in Python. This is a two-player version of the game which simply works on the background logic which basically just checks if the entered position is already taken, and update the board if not. The program then keeps on checking the current status of the game at every turn.

>Technology used: Python

>Platform: terminal/console/command prompt

>Framework used: None

>Solely because I wanted to keep this as a fairly straightforwarded application that could run on the terminal while taking the input                  from the user through built-in modules and packages of Python using promots.

Although this could be implemented in a single Python script file, I have implemented the modular apporach so that it could be modified and new funcitonalities could be added to it easily as you could see in the other repository ***"AI-Powered-Tic-Tac-Toe"***.


>_________________________________________________________________________________________________________________________________________________________


## How to run the application

Just like how you need to have **JRE** installed on your system in order to run a Java application, you need not necessarily have **JDK** installed for just running a Java application; similarly, you need to have ***Python*** installed on youer system for running this application as it provides the environment for it to run.

Download the repository on to your system and extract the project files and folders from the zip folder to the location where you want it to be in. Open your terminal/console/command prompt and navigate to the folder where the project is, then run the following command -

>python RunTicTacToe.py

Once you hit 'enter', the game starts and you see a sequence of prompts as explained in the next section.


>_________________________________________________________________________________________________________________________________________________________


## Walkthrough

Following is the sequence of prompts you get to see when you run the application -

1. *Welcome to then game of Tic-Tac-Toe!*


2. *Enter the position numbers corresponding to those in the board below...*
>You see a demo board with the position numbers set to let the user understand the corresponding values.


3. *Okay, so presenting the empty board now...*
>Then you see an empty board which is the game board.


4. *Player 1, choose your sign "x" or "o": *
>Now, Player 1 would have to choose his/her sign and the program would automatically assign the other sign to Player 2


5. *Player 1, you have chosen "x".*
>If Player 1 chooses 'x'


6. *Player 2, you are "o".*
>The program assigns 'o' automatically to Player 2.


7. *Player 1, it's your turn...*
>The prompt notifies Player 1 that it's his/her turn now.


8. *Enter position between 1 and 9, both inclusive: *
>Player 1 would then have to enter a position as described above; the program would evaluate the input and provide suitable response.


And the game goes on like this until someone wins, or is a tie. After that the prompt would ask if they want to play another round like below :-
Like in the below example, Player 1 wins and the prompt says -

>Game over! Player 1 wins!

>Do you want to play again?

If the players say yes, then the game starts over again with the same sequence of options and prompts.



>_________________________________________________________________________________________________________________________________________________________


## Error and Edge Case Handling

The prompt asks for appropirate input with the input range specified everytime. However, there could be typing errors from the users' end and so, the application is developed to be equipped to handle all the edge cases appropriately. The input range for the positions could only be 1 to 9, both inclusive. The prompt that asks the user to choose his/her sign could only rake in 'x' or 'o' as input, case insensitive. The prompt at the end of the game asks for a 'yes' or 'no', case insensitive.

There could be a variety of wrong inputs which could crash the application. Some of these are mentioned below :-
- What if the user enters an integer that is out of range of the input.
- What if the user enters 'a' instead of an integer.
- What if the user enters a digit instead of 'x' and 'o'.
- What if the user enters 'X' or 'O' when the prompt clearly mentions 'x' or 'o'.
- What if the user enters something other than 'yes' and 'no.

The application should be smart enough to take a valid input and process it accordingly. hence, the input is not restricted to case-sensitivity.



>_________________________________________________________________________________________________________________________________________________________


## Ending Note

I really hope this repository intrigues the mind for future possibilities. I have also implemented Artificial Intelligence into this game which I have uploaded in another repository called ***"AI-Powered-Tic-Tac-Toe"***. In that version, the user has an additional mode wherein he/she could play with the computer and select the difficulty of the game too. I highly encourage you to have a look at that repository too, but only after you peruse the project of this one, so that you get a better understanding of what is going on in that *AI-powered* version. I hope you learn something from this very basic implementation of the simple game of Tic-Tac-Toe, and more importantly, I really hope that you have immense fun going through it. Otherwise, it's not worth it.

Happy learning, happy coding :)
