## CS 595A Final Project

Sudoku Solver

Jonathon Khi Franse, Shubham Nipanikar, Dhruvil Vekariya

This program is designed to receive a user-inputted Sudoku puzzle of any difficulty level and solve it using a Greedy Best-First Search algorithm. While the heuristic was designed to be condition-based, as opposed to being based on a traditional mathematical function, there is still a clear fitness hierarchy to which the algorithm adheres.

No external resources or third-party code was utilized in the creation of this code.

The "puzzle" variable represents the Sudoku puzzle itself; "puzzle" will be passed to the main algorithm, where it will be manipulated until a solution is found. The zeros represent blank spaces.

To run the code, first choose an example puzzle from the "Puzzle Input" section to run through the solver by uncommenting it, or uncomment the Custom Puzzle at the bottom of the section and modify it to input your own puzzle. Then, simply run all of the Jupyter Notebook code blocks in order.

The final code block will output the solved puzzle, the number of paths that the Greedy Best-First Search algorithm explored to find the solution, and the final path itself.
