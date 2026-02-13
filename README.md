<img width="2947" height="2042" alt="image" src="https://github.com/user-attachments/assets/c9581ce9-3e17-49dd-aba2-9c5fec148809" />

🃏 Blackjack Console Game (C++)
Introduction

This project is a console-based implementation of the classic Blackjack card game written in C++.
The program allows a single player to play against a computer-controlled dealer using standard Blackjack rules.

The main purpose of this project is to demonstrate practical usage of:

Object-Oriented Programming (classes and structures)

STL containers (vector)

Random number generation (<random>)

Control flow and game logic

Input validation

Modular function design

The game runs entirely in the terminal and focuses on logic rather than graphical interface.

Principle of the Program

The core principle of the program is simulation of a real Blackjack game using structured programming and object-oriented design.

The system is built around:

Card structure → represents a single playing card

Deck class → builds, shuffles, and distributes cards

Game logic functions → calculate hand score and determine the winner

Main loop → manages betting system and repeated rounds

Randomness is implemented using std::mt19937 to ensure fair card shuffling.

The program follows a clear game cycle:

Player places a bet

Cards are dealt

Player makes decisions (Hit / Stand)

Dealer plays automatically

Result is calculated

Money is updated

Game Rules

This implementation follows standard Blackjack rules:

The goal is to get as close to 21 as possible without exceeding it.

Number cards (2–10) are worth their face value.

J, Q, K are worth 10.

Ace is worth 11, but automatically converts to 1 if the total exceeds 21.

The dealer draws cards while:

Score is less than 17

Total cards are fewer than 5

If both player and dealer bust → Push (no money change).

Equal scores → Push.

Player starts with $1000 virtual money.

How to Play

Run the program.

Enter your bet amount.

After cards are dealt:

Press h → Hit (take another card)

Press s → Stand (end your turn)

Dealer plays automatically.

The result of the round is displayed.

Choose y to continue or n to quit.

The game continues until:

The player chooses to stop, or

The player loses all money.

Conclusion

This project demonstrates how classic games can be implemented using core C++ concepts without graphical libraries.

It reinforces understanding of:

OOP design

Randomized simulations

Logical branching

Input validation

State management

The program is simple but scalable. Future improvements may include:

Blackjack (natural 21) bonus logic

Multiple players

Split and Double Down options

Persistent score system

Graphical interface version

This project serves as a solid foundation for more advanced game development in C++.
