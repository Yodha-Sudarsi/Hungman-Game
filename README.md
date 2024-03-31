# Hangman Game

Welcome to Hangman: The Game! This is a simple console-based Hangman game implemented in C++. The game randomly selects a word from a word list, generates blanks for each letter of the word, and allows players to guess letters. For each correct guess, the corresponding blank is replaced with the guessed letter. However, for each incorrect guess, a part of the hangman figure is drawn. The game continues until the player either guesses the word correctly or the hangman figure is fully drawn.

## Getting Started

### Prerequisites

- You need to have a C++ compiler installed on your system to compile and run the game.

### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your_username/hangman-game.git
Compile the hangman.cpp file using your C++ compiler:
bash
Copy code
g++ hangman.cpp -o hangman
Run the compiled executable:
bash
Copy code
./hangman

How to Play
Upon starting the game, you'll be presented with a welcome message explaining the rules and scoring system.
You'll see a series of blanks representing the letters of the randomly chosen word.
Guess letters one by one by entering them at the prompt.
For each correct guess, the corresponding blank is replaced with the guessed letter.
For each incorrect guess, a part of the hangman figure is drawn.
Continue guessing letters until you either guess the word correctly or the hangman is fully drawn.
Your score is displayed at the end of each round, indicating your performance.

Game Rules
Each correct guess awards +1 point, and each incorrect guess deducts -1 point from your score.
Guessing the full word correctly awards +2 points.
If you guess the word without making any mistakes, you receive an additional +3 points.
The maximum score you can achieve is 10 points.

Files Included
hangman.cpp: The source code for the Hangman game.
WordList.txt: A text file containing a list of words used by the game.
scores.txt: An output file that records the scores achieved by the player.

Contributing
Contributions are welcome! If you have any suggestions, bug fixes, or improvements, feel free to open an issue or submit a pull request.
