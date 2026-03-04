# Interactive Hangman Game (Python)

An educational, terminal-based game designed to demonstrate core programming concepts to K-12 students. This project follows a "learn-by-doing" philosophy, breaking down complex logic into modular, digestible components.

## 🚀 Educational Objectives
This project is used to teach students the following fundamentals:
* **Variables & Data Types:** Managing game state with integers (lives), strings (guesses), and booleans (game_over).
* **Control Flow:** Using `while` loops for the game engine and `if/elif/else` statements for win/loss logic.
* **Lists & Iteration:** Storing correct guesses and iterating through strings to update the game display.
* **Modularity:** Using the `import` statement to separate game logic from visual assets (ASCII art).

## 🛠️ Features
- **Dynamic Feedback:** Real-time updates on lives remaining and letters guessed.
- **Error Handling:** Prevents users from losing lives by guessing the same letter twice.
- **Visual Assets:** Integrated ASCII art stages to provide a visual representation of the game state.

## 📁 File Structure
- `main.py`: The core game logic and loop.
- `hangman_art.py`: Contains the `logo` and the `stages` list for the hangman visuals.
- `hangman_words.py`: A library of potential words for the random selector.

## 💻 How to Run
1. Ensure you have Python installed.
2. Clone this repository.
3. Run the following command:
   ```bash
   python main.py
