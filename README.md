# Rolling Dice Game

## Overview

Welcome to the Rolling Dice Game! This simple and entertaining game involves rolling dice to achieve specific outcomes. Whether you're a casual player looking for some fun or a serious gamer seeking a challenge, this game is designed to cater to all levels of players.

## Table of Contents

- [Features](#features)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Contributing](#contributing)
- [Resources Used](#resources-used)
- [Development enviroment](#development-environment)
- [Game Flow Chart](#game-flow-chart)
- [Flow Chart Explanation](#flow-chart-explanation)
- [Notes](#notes)
- [Fonts](#fonts)
- [Colors](#colors)
- [Icons](#icons)
- [Attribution](#attribution)

## Features

- Customizable dice configurations
- Score tracking for multiple players
- User-friendly interface
- Fun animations

## How to Play

1. **Gameplay**:

   - Click the "Roll" button to roll the dice.
   - The number rolled adds to the player's current round score.
   - If a player rolls a 1, they lose their current round score, and their turn ends. The next player in line gets a chance to roll.

2. **Scoring**:

   - Click the "Hold" button to add the current round score to your total score.
   - The turn passes to the next player after holding points.
   - Be strategic in deciding when to hold your points, as rolling a 1 forfeits your current round score.

3. **Winning**:

   - The first player to reach or exceed 100 points wins the game.

4. **Resetting**:

   - Click the "Reset" button to start a new game.
   - This resets all scores and begins with the first player.

## Installation

To Clone the repository or to play the Rolling Dice Game, follow these simple steps:

1. [To Clone the repository](#https://github.com/Petru008/Rolling-Dice-Game.git)
2. [Access the live website](#https://petru008.github.io/Rolling-Dice-Game/)

## Contributing

If you'd like to contribute to the development of the Rolling Dice Game, please follow these guidelines:

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## Resources Used

The Rolling Dice Game project is built using a combination of HTML, CSS, and JavaScript to create an engaging and interactive gaming experience. Below, we provide an overview of each technology's role in the project:

1.  **HTML**

The structure of the Rolling Dice Game is defined using HTML (Hypertext Markup Language). HTML provides the foundation for creating the various elements of the game, such as the game board, player interface, and any other essential components. The semantic structure of HTML ensures a clear and organized layout for a seamless user experience.

2.  **CSS**

CSS (Cascading Style Sheets) is employed to enhance the visual appeal of the Rolling Dice Game. Through CSS, we apply styles, colors, and animations to create an aesthetically pleasing and responsive design. The use of CSS ensures that the game is not only functional but also visually engaging, providing an immersive experience for players.

3.  **JavaScript**

JavaScript adds interactivity and dynamic behavior to the Rolling Dice Game. Through JavaScript, we implement the game logic, handle user input, and manage the game state. The randomization of dice rolls, scoring calculations, and any real-time updates are all managed through JavaScript, making the game both challenging and entertaining.

## Development Environment

The development of the Rolling Dice Game was carried out using Visual Studio Code for code editing and DevTools for testing and debugging.

By leveraging these technologies, the Rolling Dice Game delivers a rich and enjoyable gaming experience for players of all levels. Whether you're a developer interested in the project's technical aspects or a player looking to enjoy the game, understanding these resources can provide insights into the underlying technology that powers the Rolling Dice Game.

Feel free to explore the source code to gain a deeper understanding of how HTML, CSS, and JavaScript work together to bring this game to life!

## Game Flow Chart

Understanding the flow of the Rolling Dice Game is essential for players and developers alike. The following flow chart provides a visual representation of the main steps and decision points within the game:

[Dice Game Flow Chart](assets/img/rolling-dice-game-flowchart.png)

### Flow Chart Explanation

1. **Start Game:**

   - Players initiate the game by starting the application or accessing the game page.

2. **Player Setup:**

   - Players set up their game preferences, such as the first player to roll the dice.

3. **Roll Dice:**

   - Players click the "Roll" button to roll the dice.
   - The number rolled adds to the player's current round score.
   - If a player rolls a 1, they lose their current round score, and their turn ends. The next player in line gets a chance to roll.

4. **Hold Points:**

   - Players click the "Hold" button to add the current round score to their total score.
   - The turn passes to the next player after holding points.
   - Be strategic in deciding when to hold points, as rolling a 1 forfeits the current round score.

5. **Check for Winner:**

   - The game checks if any player has reached or exceeded 100 points.
   - If a player has won, the game proceeds to the "Game Over" state.

6. **Game Over:**

   - The game concludes, and the final scores are displayed. The winner is announced.
   - Players may have the option to restart the game or exit.

7. **Reset Game:**
   - Players click the "Reset" button to start a new game.
   - This resets all scores and begins with the first player.

### Notes

- **Decision Points:**

  - Decision points, where the game logic branches based on conditions, are clearly indicated in the flow chart.

- **User Interaction:**

  - Throughout the game flow, consider how users interact with the game, make decisions, and progress through each step.

Understanding this flow chart will help both players and developers navigate the Rolling Dice Game, making it an enjoyable and well-structured experience.

## Fonts

The visual appeal of the Rolling Dice Game is enhanced by thoughtfully chosen fonts that contribute to the game's aesthetics and readability. The following fonts are used in various elements of the game:

1. **Primary font**: [Nunito](#https://fonts.google.com/specimen/Nunito?query=nunito)
2. **Second font**: Sans-serif

## Colors

The color scheme of the Rolling Dice Game is carefully curated to create an appealing visual experience and convey a specific mood. The following colors are used throughout the game:

- **Primary Color**: #023e8a,#03045e,#90e0ef
- **Secondary Color**: #caf0f8, #000
- **Background Color**: rgba(173, 232, 244, 0.8), rgba(2, 61, 138, 0.4), #caf0f8, #ade8f4,rgba(0, 29, 61, 0.6), rgba(0, 0, 0, 0.2)
- **Box Shadow Color**: rgba(0, 0, 0, 0.25), rgba(2, 61, 138, 0.15), rgba(2, 61, 138, 0.2), rgba(2, 61, 138, 0.1)
- **Icons**: rgba(191, 6, 3, 0.656)
- **Hover Color** : #90e0ef

## Icons

We use the following icons resources to build this project:

- [Font Awesome](#https://fontawesome.com/icons)

  
## Attribution 

- Code for sticky navigation was partially used from: [W3Schools](#https://www.w3schools.com/howto/howto_js_navbar_sticky.asp)
- Part of the project was inspired from: [James Schmedtmann](#https://github.com/jonasschmedtmann/complete-javascript-course/tree/master/07-Pig-Game)
