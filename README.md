# Turtle Race Game
Welcome to the Turtle Race Game! 🐢🏁 This is a fun project that simulates a race between five turtles using the Python turtle module. Users can place a bet on which turtle they think will win the race, and the game will display the result based on the turtle that crosses the finish line first.

## Features
- User can input a bet on the color of the turtle they think will win.
- Five turtles race across the screen, with each turtle moving a random distance in each iteration.
- The game announces the winner and whether the user's bet was correct or not.

## Requirements
- Python 3.x
- turtle module (usually included with Python)

## How It Works
- When the game starts, a window will open asking you to input your bet. Enter the color of the turtle you think will win.
- Five turtles of different colors will line up at the start line.
- The turtles will race towards the finish line, and their movement is controlled by random distances.
- Once a turtle crosses the finish line, the game will display the result, indicating which turtle won and whether your bet was correct.

## Code Explanation
- Imports: Turtle and Screen from the turtle module are used to create and control the turtles and the game window. The random module is used to generate random distances for the turtles to move.
- Setup: The screen is set up with a width of 500 and a height of 400. Turtles are created with different colors and positioned at the start line.
- Race Logic: The turtles move forward by random distances in a loop until one of them crosses the finish line. The game then checks if the winning turtle's color matches the user's bet.

## Contributing
- Feel free to fork this repository and submit pull requests with improvements or fixes. For major changes, please open an issue to discuss them first.
