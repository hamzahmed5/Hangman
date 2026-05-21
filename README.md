# 🎮 Hangman Game

A classic terminal-based Hangman game written in Python with beautiful ASCII art and an extensive word dictionary.

## 📋 Overview

This is an interactive command-line implementation of the popular word-guessing game Hangman. Players have 6 lives to guess the hidden word letter by letter before the hangman drawing is complete.

## ✨ Features

- **Interactive Gameplay**: Guess letters one at a time to reveal the hidden word
- **ASCII Art Graphics**: Visual hangman stages that progressively display as you lose lives
- **Extensive Word List**: Hundreds of unique words to keep games interesting
- **Live Counter**: Track remaining attempts with a clear display
- **Game States**: Win/lose conditions with appropriate messages
- **User-Friendly**: Simple command-line interface for easy gameplay

## 🎯 How to Play

1. **Start the Game**: Run the main Python file
2. **Guess Letters**: Enter one letter at a time when prompted
3. **Track Progress**: Watch the word reveal as you guess correctly
4. **Avoid Wrong Guesses**: Each wrong guess costs you 1 life (6 total)
5. **Win Condition**: Reveal the entire word before running out of lives
6. **Lose Condition**: Game ends when lives reach 0

### Game Rules

- You start with **6 lives**
- Each incorrect guess costs **1 life**
- Guessing the same letter twice triggers a warning
- The hangman drawing completes as you lose lives
- Correctly guess the word before the drawing is finished to win

## 📁 Project Structure

```
Hangman/
├── Hange_Man.py              # Main game logic and flow
├── hangman_art.py            # ASCII art for hangman stages and logo
├── hangman_words.py          # Word list for game
└── README.md                 # Documentation
```

### File Descriptions

- **Hange_Man.py**: Contains the core game loop, user input handling, and win/lose logic
- **hangman_art.py**: Stores the 7 ASCII art stages of the hangman and the game logo
- **hangman_words.py**: Contains a comprehensive word list for random word selection

## 🚀 Installation & Usage

### Prerequisites

- Python 3.x installed on your system

### Running the Game

```bash
# Navigate to the project directory
cd Hangman

# Run the game
python "Hange_Man.py"
```

That's it! The game will start immediately with the ASCII logo and wait for your first guess.

## 🎨 ASCII Art Features

The game includes:
- **Game Logo**: Displays at game start
- **7 Hangman Stages**: Progressively shows the hangman as you lose lives:
  - Stage 0: Complete hangman (loss)
  - Stage 6: Empty gallows (fresh start)

## 📊 Word Difficulty

The word list includes a variety of English words with different lengths and difficulty levels, ensuring varied and challenging gameplay.

## 🎓 Learning Opportunities

This project demonstrates:
- **Control Flow**: While loops and conditional statements
- **Data Structures**: Lists and strings
- **Imports**: Using custom modules in Python
- **User Input**: Interactive input/output
- **ASCII Art**: Creative use of string formatting
- **Game Logic**: State management and game flow

## 🔧 Future Enhancements

Possible improvements for future versions:
- Difficulty levels with different word categories
- Score tracking and high scores
- Hint system
- Category selection
- Replay functionality without restarting
- Multiplayer mode
- Word categories (animals, countries, etc.)

## 📝 License

This project is open source and available for personal and educational use.

## 👤 Author

Created by [Hamza Ahmed](https://github.com/hamzahmed5)

## 🤝 Contributing

Feel free to fork this project, make improvements, and submit pull requests!

---

**Enjoy the game and have fun! 🎉**
