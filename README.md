## Blackjack Game
Welcome to the Blackjack Game! This is a simple text-based implementation of the classic card game Blackjack, where you play against the computer. The objective is to get a hand value as close to 21 as possible without exceeding it.

# Introduction
This Blackjack game is a console-based game written in Python. The game is played against the computer, and the goal is to beat the computer by getting a hand that is closer to 21 without going over.

# Rules
The player and the computer are each dealt two cards initially.
Cards are valued as follows:
Number cards (2-10) are worth their face value.
The Jack, Queen, and King are each worth 10.
The Ace can be worth 11 or 1, depending on which value benefits the hand more.
If the player's or computer's hand has a total value of 21 with the first two cards (an Ace and a 10-value card), it's a Blackjack.
The player can choose to "hit" (draw another card) or "stand" (keep their current hand).
The computer must hit until its hand value is 17 or higher.
The winner is determined based on whose hand is closest to 21 without exceeding it.

# How to Play
When the game starts, you will be asked if you want to play a game of Blackjack. Type 'y' to play or 'n' to exit.
You will be dealt two cards, and the computer will be dealt two cards.
You will see your cards and one of the computer's cards.
You can choose to hit ('y') to get another card or stand ('n') to keep your current hand.
The game will continue until you or the computer wins or busts (goes over 21).

# Requirements

    Python 3.x
    The art module (for the ASCII logo)

## Installation
# Clone the repository to your local machine.

    git clone [https://github.com/yourusername/blackjack-game.git](https://github.com/YKirianova/Simple-Blackjack-Project)

# (Optional) Create a virtual environment.

    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install the required dependencies.

    pip install -r requirements.txt

# Usage

To start the game, simply run the blackjack.py file.

    python blackjack.py

Follow the on-screen instructions to play the game. Enjoy your time beating the computer!

