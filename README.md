# Connect 4 Game with AI Agent 

A classic Connect 4 game developed in Python, featuring an intelligent AI opponent built with advanced Artificial Intelligence algorithms. This project was developed as part of the academic coursework at the Faculty of Computers and Artificial Intelligence, Helwan University.

##  Project Overview
The game consists of a vertical grid with 6 rows and 7 columns. The objective is to align four identically colored pieces horizontally, vertically, or diagonally before your opponent does. 

The core feature of this project is the AI agent, which is designed to be highly competitive by utilizing the **Minimax Algorithm** optimized with **Alpha-Beta Pruning**.

##  Key Features
* **Interactive GUI:** Built using Pygame and NumPy for a smooth visual experience.
* **Advanced AI Opponent:** The AI evaluates all possible moves recursively to maximize its advantage while minimizing the player's chances.
* **Alpha-Beta Pruning:** Eliminates unnecessary branches in the game tree, significantly reducing computation time without affecting the final strategic decision.
* **Custom Heuristic Functions:** * *Evaluate Window:* Scores specific sub-grids (windows of 4 consecutive cells) to determine favorable positions.
  * *Score Position:* Evaluates the entire board state by aggregating scores from all possible windows, guiding the AI to the optimal move.

## How to Play

### Option 1: Play Directly (No Setup Required)
If you just want to play the game without installing Python or any libraries:
1. Go to the **Releases** section on the right side of this repository.
2. Download the `Connect Four Game.exe` file.
3. Double-click the file to start playing immediately against the AI!

### Option 2: Run from Source (For Developers)
If you want to view the code and run it via Python:
1.  Clone this repository to your local machine:
    ```bash
    git clone https://github.com/beshomagdy2050/AI-Powered-Connect-4-Agent.git

2.  Navigate to the project directory and install the required dependencies:
    bash
    pip install -r requirements.txt

3.  Run the game script:
    bash
    python connect_four_game.py

Developed at Helwan University - Faculty of Computers and Artificial Intelligence