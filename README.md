# Number Guessing Game 🎮

A simple, interactive command-line Number Guessing Game built with Python. The program generates a random number within a specified range, and the player tries to guess it with real-time feedback.

## Features ✨

* **Dynamic Feedback**: Tells the player if their guess is too high or too low.
* **Score Tracking**: Counts the number of attempts it took to guess correctly.
* **Input Validation**: Prevents the game from crashing if the user enters letters instead of numbers.
* **Replay Option**: Allows players to start a new game instantly without restarting the script.

## Getting Started 🚀

### Prerequisites

You need Python 3.x installed on your system. You can check your version by running:

```bash
python --version
```

### Installation & Running the Game

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```

2. **Navigate into the project directory:**
   ```bash
   cd NUMBER_GUESSING_GAME
   ```

3. **Run the script:**
   ```bash
   python main.py
   ```

## How to Play 🕹️

1. The game will randomly select a secret number between 1 and 100.
2. Type your guess in the terminal and press `Enter`.
3. The game will guide you by saying **"Too high!"** or **"Too low!"**.
4. Keep guessing until you find the correct number!
5. View your total score (attempts) at the end and choose to play again or exit.

## Roadmap 🗺️

Future improvements planned for this project:
- [ ] Add difficulty levels (Easy, Medium, Hard) to change the number range.
- [ ] Implement a maximum limit of guesses (e.g., game over after 5 failed attempts).
- [ ] Build a Graphical User Interface (GUI) using Tkinter.

## License 📄

This project is open-source and available under the [MIT License](LICENSE).
