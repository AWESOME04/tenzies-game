# Tenzies Game

![image](https://github.com/AWESOME04/tenzies-game/assets/102630199/97321f8d-ca60-4f52-a0fd-58d5c18d325a)

This is a React-based web application that implements the game of Tenzies. Tenzies is a game where the player rolls dice and tries to get all the dice to display the same number. The game continues until the player achieves this goal.

## How to Play

1. Roll the dice by clicking the "Roll" button.
2. Click on any die to "hold" it at its current value. This will prevent that die from being re-rolled on the next roll.
3. Keep rolling and holding dice until all the dice display the same number.
4. Once all the dice show the same number, you've won! Click "New Game" to start a new round.

## Features

- Roll and hold dice functionality
- Confetti celebration when the game is won
- Responsive design for different screen sizes

## Technologies Used

- React
- React Hooks (useState, useEffect)
- nanoid (for generating unique IDs)
- react-confetti (for the confetti animation)

## Future Improvements
- Add an authentocation to allow users sign up / log in to see older gameplays
- Allow users to choose from different color themes.
- Add a multiplayer mode for players to compete against each other in real-time or take turns.
- Introduce different difficulty levels by varying the number of dice or target value.
- Add visually appealing animations and sound effects for dice rolling, winning, and other actions.
- Track and display game statistics and analytics for players, such as games played, average score, and win/loss ratio.

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/AWESOME04/tenzies-game.git`
2. Navigate to the project directory: `cd tenzies-game`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`

The application should now be running at `http://localhost:3000`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
