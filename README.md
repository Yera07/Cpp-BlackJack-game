# Cpp-BlackJack-game
The BlackJack game written in C++
Вот готовый, аккуратно оформленный текст для README.md. Можно вставлять прямо в GitHub.

🃏 Blackjack Console Game (C++)
📌 Overview

This project is a console-based implementation of the classic Blackjack (21) card game written in C++.
The player competes against a computer-controlled dealer using standard Blackjack rules.

The game focuses on logic, object-oriented programming, and clean structure rather than graphics. It demonstrates how a real card game can be simulated using core C++ concepts.

🎯 Project Purpose

The main goal of this project is to apply and demonstrate:

Object-Oriented Programming (classes and structures)

STL containers (std::vector)

Random number generation (std::mt19937)

Conditional statements and loops

Input validation

Modular and readable code design

This project is suitable for beginner and intermediate C++ students.

⚙️ How It Works (Program Principle)

The game simulates a real Blackjack round using structured logic:

Card structure represents a playing card (rank + suit)

Deck class builds, shuffles, and deals cards

handScore() calculates the total score of a hand

Dealer logic automatically draws cards according to rules

A betting system manages player balance

Each round follows this sequence:

Player places a bet

Deck is shuffled

Two cards are dealt to player and dealer

Player chooses to Hit or Stand

Dealer plays automatically

Winner is determined

Balance is updated

📝 Game Rules

Goal: Get as close to 21 as possible without exceeding it.

Number cards (2–10) = face value.

J, Q, K = 10.

Ace = 11 or 1 (automatically adjusted to prevent bust).

Dealer draws cards while score < 17.

If player score > 21 → Player busts.

If dealer score > 21 → Dealer busts.

Equal scores → Push (no money change).

Player starts with $1000 virtual balance.

▶️ How to Play

Compile and run the program.

Enter your bet amount.

During your turn:

Type h to Hit (take another card)

Type s to Stand (end your turn)

After the dealer plays, results are shown.

Type y to continue or n to exit.

The game continues until:

The player quits, or

The balance reaches $0.

💻 Compilation

Using g++:

g++ main.cpp -o blackjack
./blackjack


Make sure your compiler supports C++11 or higher.

🚀 Possible Improvements

Future enhancements may include:

Blackjack (natural 21) bonus payout

Split and Double Down options

Multiple players

Persistent score saving

Graphical user interface (GUI)

Statistics tracking

📚 Educational Value

This project strengthens understanding of:

Game state management

Randomized simulations

Clean class design

Console user interaction

Practical use of STL

It serves as a solid foundation for more advanced C++ projects and game development.
