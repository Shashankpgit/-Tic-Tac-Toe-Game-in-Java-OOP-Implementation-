# -Tic-Tac-Toe-Game-in-Java-OOP-Implementation-

This project is a console-based Tic-Tac-Toe game developed using Object-Oriented Programming (OOP) principles in Java. It serves as both a practical example of OOP concepts and a fun game to play. The project features both human and AI players, providing a flexible gaming experience where a player can compete against another human or challenge the computer.

Key Features:
Object-Oriented Design: The game is built around OOP principles, with clear separation of concerns. The main components include a `TicTacToe` class for managing the game board and overall logic, an abstract `Player` class, and specific subclasses for `HumanPlayer` and `AIPlayer`.
  
Human vs. AI Gameplay: The game supports two modes—Human vs. Human and Human vs. AI. The AI player makes moves based on random selections, providing a basic but challenging opponent for human players.
Interactive User Interface: The game runs in the console, with a simple text-based interface that prompts players to input their moves. The board is displayed after each move, showing the current state of the game.
Win and Draw Detection: The game includes logic to check for winning conditions across rows, columns, and diagonals, as well as the ability to detect a draw when all board positions are filled with no winner.

Code Structure:
- The TicTacToe class manages the board and game rules, ensuring that moves are valid and determining the outcome of the game.
- Player is an abstract class that defines the common behavior for all players, with concrete implementations in the "HumanPlayer"and "AIPlayer" classes, encapsulating player-specific logic.
- The game loop in the "Main" class alternates turns between players, checks for game-ending conditions, and handles user inputs, keeping the gameplay smooth and intuitive.

This modular approach makes the code easy to read, maintain, and extend, making it a strong example of OOP in practice.
