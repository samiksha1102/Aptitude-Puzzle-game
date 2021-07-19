# Aptitude-Puzzle-game
Sudoku/Magic square puzzle for elementry school children
The Aptitude Puzzle will be designed for the students of elementary schools, keeping in
mind their need for development of logical and mathematical skills. The main purpose of this
project is to provide challenging puzzles that will help the quantitative ability of the students and
aid them in various competitive examinations

Technical Approach:

The problem statement requires us to build a game simulation. The initial objective for
the preparation was to display the puzzle on a Graphic LCD and allow the user to input the
desired answer on the display via keypad. For solving the puzzle, the user also requires
navigating through various boxes on the display and a device for navigation is needed for the
same.
The selection of components was based on comparison of specifications of various
devices. After finalisation of components, the team was involved in the logic development for
the code required in the circuit. The code for the simulation was written in Embedded C.

WORKING:

The device starts by clicking on the C/ON button on the 4x4 matrix i.e the keypad. The
screen displays “Welcome” on starting the device. To continue with the game the player has to
press enter or C/ON. A 3x3 matrix displayed on the screen which can be navigated throughby
block selection method i.e. to move to the 1st block in the 3x3 matrix the player has to long press
button 1 on the keypad to move the cursor on it and then press the number which it wants to
display on the screen. Once the matrix is completed i.e. when the sum of all rows, columns and
diagonals are equal to 15 a message will be displayed with “You won” and “Press enter to
reset”. The game has 8 different methods to solve it, simply by rotating it by diagonals and the
center rows and columns. The player has to enter any one sequence of numbers to win. If C/ON
is pressed again the device will reset and the game starts again.
