# Guessing-Game

The Guessing-Game is a fun and interactive Python project designed to challenge your guessing skills. It is suitable for both beginners and experienced programmers looking to enhance their Python skills. This project offers two different modes: **Basic** and **Advanced**.

## Table of Contents
- [Project Goals](#project-goals)
- [Motivation](#motivation)
- [Basic Mode](#basic-mode)
- [Advanced Mode](#advanced-mode)
- [How to Run](#how-to-run)


## Project Goals

The primary goals of this project are:

- **Education:** To provide an educational resource for those learning Python, demonstrating essential concepts such as conditional statements, random number generation, and user input handling.

- **Entertainment:** To create an enjoyable gaming experience that keeps players engaged and motivated to improve their guessing skills.

- **Customization:** To offer two distinct game modes, catering to different levels of difficulty and player preferences.


## Motivation

The Guessing-Game project was born out of a passion for both programming and gaming. It serves as an example of how programming can be used to create interactive and entertaining applications. By sharing this project with the community, we hope to inspire others to explore the world of game development and foster a love for coding.


## Basic Mode

In the Basic mode, the game randomly selects an integer between 1 and 100, and your task is to guess the number. Here are the basic rules:

- If your guess is less than 1 or greater than 100, you'll receive a message saying "OUT OF BOUNDS."
- On your first turn, if your guess is within 10 of the number, you'll get a "WARM!" message.
- If your guess is further than 10 away from the number, you'll receive a "COLD!" message.
- On subsequent turns:
  - If your guess is closer to the number than your previous guess, you'll be notified with "WARMER!"
  - If your guess is farther from the number than your previous guess, you'll see "COLDER!"

## Advanced Mode

The Advanced mode builds upon the Basic mode by adding a few more features:

- If your guess is within 2 of the number, you'll receive an even more enthusiastic "VERY WARM!" message.
- When you correctly guess the number, the program will not only confirm your success but also tell you how many guesses it took.

## How to Run

To enjoy the Python Guessing Game, follow these steps:

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/Ishika63/Guessing-Game.git

2. Navigate to the project directory:

   ```shell
   cd Guessing-Game

3. Choose the mode you want to play by running the corresponding Python script:

- Basic Mode:

   ```shell
   python GuessingGame_Basic.py

- Advanced Mode:

   ```shell
   python GuessingGame_Advanced.py

4. Follow the on-screen instructions to guess the number and enjoy the game!
