# Real-Time-Sudoku-Solver-Using-ML
Real-Time Sudoku Solver using OpenCV and Keras
This Python application solves Sudoku puzzles in real time by overlaying the solution onto the actual image of the puzzle.

--Overview
This project is inspired by AnhMinhTran's YouTube video and utilizes computer vision and deep learning to recognize, solve, and display the solution on live camera feed.

--Key Features
Real-Time Processing: Detects and solves Sudoku puzzles directly from the camera feed.
Optimized Algorithm: Implements a Greedy Best First Search approach—an enhancement over the traditional backtracking method, which reduces computational complexity by prioritizing cells with the fewest possibilities.



--How to Run
Install Dependencies:
Install the required libraries by running:
bash
Copy code
pip install -r requirements.txt
Run the Notebook:



Open the Sudoku_testing.ipynb file and execute all the cells in sequence. This will handle all necessary imports and start the application.



--Solve the Puzzle:
Point your camera at a Sudoku puzzle. The solution will be dynamically overlayed on the detected grid.
--Stop the Camera:
To exit the camera feed, press the 'Q' key.




#Output Example
The application identifies the Sudoku grid from a live camera feed, solves it, and displays the solution directly on the captured image.
This project showcases a blend of computer vision techniques with real-time deep learning, offering an interactive way to solve Sudoku puzzles effortlessly.






