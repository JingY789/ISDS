# ISDS
Summary
Rebecca has asked for your help with another puzzle page. This page involves solving the Hitori puzzle. The Hitori puzzle is played on a grid of numbers. Each number is either circled or darkened; a darkened cell is referred to as a block. 

A successful solution will meet these three criteria:
1.	The same number cannot be circled more than once in any row or column.
2.	Blocks cannot touch horizontally or vertically, though they may be placed diagonally to one another.
3.	Circled numbers must complete a continuous path throughout the grid; no circled number or group of circled numbers can be isolated from the others by a line of blocks.

Rebecca wants you to create an interface for this puzzle similar to the one you created for the Hanjie puzzle. She already has stored three puzzles in a JavaScript file named jpf_grids3.js, and within that file she has created the following variables: • hitori1Rating through hitori3Ratingcontaining the difficulty ratings of the puzzles •hitori1Numbers through hitori3Numberscontaining the numbers in the puzzle grids • hitori1Blocks through hitori3Blocksspecifying the location of the blocks in the puzzle grids 

Rebecca has provided you with the following functions: • drawHitori(), which writes the HTML code of the puzzle table given the puzzle numbers, location of the puzzle blocks, and the puzzle rating • checkSolution(), which returns an alert box indicating whether the puzzle has been solved • showSolution(), which displays the puzzle solution

Your job will be to complete the application by writing the code that displays the puzzle and provides users with an interface to solve it.
