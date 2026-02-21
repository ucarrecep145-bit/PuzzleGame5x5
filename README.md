# Puzzle Game 5x5

## Project Documentation

### Project Structure
```
PuzzleGame5x5/
│
├── src/
│   ├── main.py             # Main game logic
│   ├── game.py             # Game class and gameplay functions
│   └── utils.py            # Utility functions
│
├── tests/
│   ├── test_game.py        # Unit tests for game logic
│   └── test_utils.py       # Unit tests for utility functions
│
├── README.md               # Project documentation
├── requirements.txt         # Python dependencies
└── LICENSE                  # License information
```

### Blueprint Descriptions
- **Main.py**: The entry point of the application that starts the game.
- **Game.py**: Contains the core logic of the puzzle game, including setting up the puzzle, handling player moves, and checking for win conditions.
- **Utils.py**: Holds various utility functions that help in managing the game, such as randomizing puzzle pieces and validating user input.
- **Tests**: A directory containing unit tests to ensure the game logic is functioning as expected.

### Features
- 5x5 puzzle gameplay.
- Randomized puzzle generation each game.
- User-friendly interface for player interaction.
- Win condition detection and celebratory message upon completion.
- Unit tests for reliable code functionality.

### Getting Started Guide
1. **Clone the repository**:
   ```bash
   git clone https://github.com/ucarrecep145-bit/PuzzleGame5x5.git
   cd PuzzleGame5x5
   ```
2. **Install dependencies**:
   Make sure you have Python installed. Then run:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the game**:
   Start the game by executing:
   ```bash
   python src/main.py
   ```

Enjoy the challenge of the Puzzle Game 5x5!