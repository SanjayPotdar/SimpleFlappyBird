# Flappy Bird Clone

This project is a simplified version of the popular game **Flappy Bird**, developed using basic concepts of **Phaser.js**. It's designed as an introduction to essential game mechanics, offering insight into sprite movement, collision detection, physics, and state management. The code serves as a foundation for building and prototyping your own 2D games.

## Table of Contents
- [Demo](#demo)
- [Installation](#installation)
- [Project Structure](#project-structure)

## Demo
To play the game, you will need to run it using a live server. Open the `index.html` file in any modern web browser using a live server extension,
or you can play it directly [here](https://sanjaypotdar.github.io/SimpleFlappyBird/).



## Installation
To get started, follow these steps:

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/SanjayPotdar/SimpleFlappyBird.git
    ```
2. Navigate into the project directory:
    ```bash
    cd flappy-bird-clone
    ```
3. Open the project in your code editor and start a live server to play the game.

### Example Customizations:
- **Change Visual Assets:** Swap out the bird or columns with your own images.
- **Implement Scoring:** Introduce a scoring mechanism based on gameplay performance.
- **Expand Levels:** Add additional levels or obstacles to enhance the challenge.

## Project Structure
FlappyBird/              
├── assets/              
│ ├── background.png # Background image for the game                  
│ ├── bird.png # Bird sprite for animation                            
│ ├── column.png # Column used as an obstacle                         
│ └── road.png # Road at the bottom of the screen                     
├── index.html # Main HTML file                                       
└── app.js # Game logic and Phaser.js code                            
