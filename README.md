# Guess My Number

Welcome to the "Guess My Number" game! This is a simple interactive game built with HTML, CSS, and JavaScript, where players try to guess a randomly generated number between 1 and 20.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Demo

You can play the game online [here](#). *(Replace `#` with the link to your live demo if available.)*

## Features

- Random number generation between 1 and 20.
- Interactive input for user guesses.
- Feedback messages guiding the player ("Too high!", "Too low!", "Correct number!").
- Score tracking for each game session.
- Highscore tracking across sessions.
- Option to restart the game at any time.

## How to Play

1. The game generates a secret number between 1 and 20.
2. Enter your guess in the input field.
3. Click the "Check!" button to submit your guess.
4. The game will provide feedback:
   - 🎉 Correct Number! – if your guess is correct.
   - 📈 Too high! – if your guess is higher than the secret number.
   - 📉 Too low! – if your guess is lower than the secret number.
5. Your score decreases with each incorrect guess.
6. Click the "Again!" button to restart the game at any time.

## Installation

To run the game locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/guess-my-number.git
   ```
2. Navigate to the project directory:
   ```bash
   cd guess-my-number
   ```
3. Open `index.html` in your preferred web browser.

## Usage

Feel free to explore and modify the code to enhance the game or add new features. The main files are:

- `index.html` – the main HTML structure.
- `style.css` – the styling for the game.
- `script.js` – the game logic implemented in JavaScript.

## Contributing

Contributions are welcome! If you'd like to improve the game or fix bugs:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add feature name'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request detailing your changes.

## Acknowledgements

- Inspired by the JavaScript guessing game tutorial on [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash).
