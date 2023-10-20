# Aim Training Game

This is a simple JavaScript-based game where the objective is to click on randomly generated circles within a specified time limit. The game keeps track of your score, which increases every time you successfully click on a circle.

## Getting Started

To get started with the game, simply open the provided HTML file in a web browser. You will see a "Start" button. Click on it to begin the game.

## Game Rules

- You will be presented with a list of time options. Choose one to set the time limit for the game.
- Click on the circles as quickly as you can to increase your score.
- The game ends when the timer reaches zero.

## How to Play

- Click on the circles that appear on the board.
- Each successful click increases your score.
- Try to get the highest score possible before the timer runs out.

## Code Overview

Here's an overview of the code:

- `startBtn`: This variable represents the start button element.
- `screens`: Represents an array of screens, which are sections of the game interface.
- `timeList`: Refers to the list of time options.
- `timeEl`: Represents the element displaying the remaining time.
- `board`: Refers to the game board where circles appear.
- `colors`: An array of colors used for the circles.

The code contains event listeners for the start button, time options, and the game board. It also includes functions for starting the game, decreasing time, setting the time display, finishing the game, creating random circles, generating random numbers, and selecting random colors.

Additionally, there's an optional function `winTheGame` that automatically clicks on circles to simulate winning the game.

## Customization

If you'd like to customize the game, you can:

- Adjust the `colors` array to include your preferred colors.
- Modify the time options or set a default time.
- Change the appearance of the circles or the board by adjusting the CSS.

## Auto-Speed Game

The `winTheGame` function provides an automated way to play the game at maximum speed. It continuously clicks on circles, simulating a perfect player.

## Have Fun!

Enjoy playing the Circle Clicker Game! If you have any questions or suggestions, feel free to reach out. Happy clicking!
