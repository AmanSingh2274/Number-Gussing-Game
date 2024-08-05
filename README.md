# Number-Gussing-Game
Welcome to the Number Guessing Game repository! This project is a simple Java-based game where the player tries to guess a randomly generated number within a given range. The game provides feedback on whether the guessed number is too high, too low, or correct.

## Table of Contents
Features
Requirements
Installation
Usage
Contributing
License
## Features
Randomly generates a number within a specified range.
Provides feedback on each guess (too high, too low, correct).
Tracks the number of attempts taken to guess the number correctly.
Allows the player to play multiple rounds.
## Requirements
Java Development Kit (JDK) 8 or higher
## Installation
### Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/number-guessing-game.git
### Navigate to the project directory:

bash
Copy code
cd number-guessing-game
### Compile the Java source files:

bash
Copy code
javac src/com/numberguessinggame/*.java
### Usage
Run the game:

bash
Copy code
java -cp src com.numberguessinggame.Main
Follow the on-screen instructions to guess the number.

## Project Structure
css
Copy code
number-guessing-game/
├── src/
│   └── com/
│       └── numberguessinggame/
│           ├── Main.java
│           ├── Game.java
│           └── Utils.java
├── README.md
└── LICENSE
Main.java: Contains the main method and initializes the game.
Game.java: Handles the game logic, including number generation and user interaction.
Utils.java: Contains utility methods used in the game.
## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any feature additions, bug fixes, or improvements.

## Fork the repository

Create your feature branch:

bash

Copy code

git checkout -b feature/your-feature

Commit your changes:


bash

Copy code

git commit -m 'Add some feature'

Push to the branch:


bash

Copy code

git push origin feature/your-feature

Open a pull request


## License
This project is licensed under the MIT License. See the LICENSE file for details.

Happy guessing!
