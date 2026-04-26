❌⭕ Tic Tac Toe — Java Console Game
A fully playable Tic Tac Toe game built in Java, supporting both Human vs Human and Human vs AI modes. Developed using Eclipse IDE and built with core Object-Oriented Programming principles.

🎮 Gameplay Preview
-----TIC TAC TOE GAME-----

Enter Player1 Name: Diwakar
Want to play with Human or Ai: Ai
Start the Game--->

+-------+-------+-------+
|       |       |       |
+-------+-------+-------+
|       |       |       |
+-------+-------+-------+
|       |       |       |
+-------+-------+-------+

Diwakar Turn
Enter Row and Column: 1 1

+-------+-------+-------+
|       |       |       |
+-------+-------+-------+
|       |   X   |       |
+-------+-------+-------+
|       |       |       |
+-------+-------+-------+

Ai Turn...

+-------+-------+-------+
|   O   |       |       |
+-------+-------+-------+
|       |   X   |       |
+-------+-------+-------+
|       |       |       |
+-------+-------+-------+

✨ Features

🧑 Human vs Human — Two players take turns on the same machine
🤖 Human vs AI — Play against a computer opponent (random strategy)
✅ Win Detection — Checks rows, columns, and both diagonals
🤝 Draw Detection — Detects when the board is full with no winner
🚫 Input Validation — Prevents overwriting an already occupied cell


🗂️ Project Structure
com.TicTacToe/
├── TicTacToe.java      # Board logic, win/draw checks
├── Player.java         # Abstract Player class with move validation
├── HumanPlayer.java    # Human player — takes input from console
├── AIPlayer.java       # AI player — makes random valid moves
└── LaunchGame.java     # Main entry point — game loop & setup

All classes are written in a single file for simplicity.


🧱 OOP Concepts Used
ConceptWhere UsedClasses & ObjectsTicTacToe, HumanPlayer, AIPlayerAbstract ClassPlayer — defines makeMove() contractInheritanceHumanPlayer and AIPlayer extend PlayerEncapsulationBoard state managed inside TicTacToePolymorphismPlayer cp holds either HumanPlayer or AIPlayer

🚀 How to Run
Prerequisites

Java JDK 8 or higher
Eclipse IDE (or any Java IDE / terminal)

Option 1 — Run in Eclipse

Clone the repository

bash   git clone https://github.com/your-username/TicTacToe.git

Open Eclipse → File → Import → Existing Projects into Workspace
Select the cloned folder
Right-click LaunchGame.java → Run As → Java Application

Option 2 — Run via Terminal
bashjavac LaunchGame.java
java com.TicTacToe.LaunchGame

🕹️ How to Play

Enter your Player 1 name
Choose opponent — type Ai to play against the computer, or anything else for a second human player
On your turn, enter the row and column (0–2) separated by a space
First to get 3 in a row (horizontally, vertically, or diagonally) wins!

Board Positions Reference
(0,0) | (0,1) | (0,2)
(1,0) | (1,1) | (1,2)
(2,0) | (2,1) | (2,2)

🛠️ Built With

Java — Core language
Eclipse IDE — Development environment
java.util.Scanner — Console input
java.util.Random — AI random move generation


🔮 Future Improvements

 Implement Minimax algorithm for unbeatable AI
 Add a graphical UI using JavaFX or Swing
 Score tracking across multiple rounds
 Difficulty levels (Easy / Medium / Hard)


👤 Author

Replace with your name and GitHub profile URL.


📄 License
This project is open source and available under the MIT License.
