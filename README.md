# Logic Leap Game - README

Welcome to the Logic Leap Game! This is a fun and educational game that challenges players to test their knowledge of logical propositions while avoiding obstacles. In this README, you'll find all the necessary information to set up and play the game, as well as guidance on contributing to the project.

## Table of Contents

- [Project Overview](#project-overview)
- [Game Setup](#game-setup)
- [Game Instructions](#game-instructions)
- [Scoring and Lives](#scoring-and-lives)
- [Game Over and Replay](#game-over-and-replay)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Logic Leap Game is a 2D side-scrolling game where players must answer logical propositions to keep the character alive and earn points. Incorrect answers or collisions with obstacles result in a loss of lives. The game uses HTML, CSS, and JavaScript to create a visually appealing and interactive experience.

## Game Setup

To run the Logic Leap Game on your local environment, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/logic-leap-game.git
   ```

2. Change into the project directory:
   ```bash
   cd logic-leap-game
   ```

3. Open `game.html` in your web browser, or serve the project using a local web server. You can use Python's `http.server` or Node.js's `http-server` to host the game locally:
   ```bash
   # Using Python
   python -m http.server
   
   # Using http-server (if installed via npm)
   http-server
   ```

4. Open the provided URL in your web browser to start playing the game.

## Game Instructions

The Logic Leap Game is designed to test your logical reasoning skills. Here's how to play:

- **Controls**: Use the "True" and "False" buttons to answer the logic-based propositions.
- **Propositions**: A proposition will appear as an obstacle. Determine if the proposition is true or false and click the appropriate button.
- **Player Movement**: Answering correctly causes the player character to jump over obstacles.
- **Lives**: You start with three lives, represented by ❤️. Incorrect answers or collisions with obstacles will reduce your lives.

## Scoring and Lives

- **Score**: Your score increases each time you answer correctly. The objective is to achieve the highest score possible.
- **Lives**: You have three lives. Each time you collide with an obstacle or answer a proposition incorrectly, you lose a life.

## Game Over and Replay

When you lose all three lives, the game ends and a "Game Over" popup appears with your final score. Click the "Play Again" button to reset the game and start over.

## Contributing

Contributions are welcome! To contribute to the project:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bugfix.
3. Implement your changes and commit them with descriptive messages.
4. Push your branch to GitHub and open a Pull Request.

Make sure your contributions align with the project's coding standards and contribute positively to the game's functionality.

## License

This project is licensed under the [MIT License](LICENSE). You can use, modify, and distribute the code, but any derived works must also be licensed under the same terms.

---

Thank you for playing the Logic Leap Game! If you have any questions or feedback, please create an issue on GitHub or reach out to the project maintainers.
