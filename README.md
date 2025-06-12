# 🕹️ Hangman Game (OOP Version)

A terminal-based Hangman game built in Python, leveraging object-oriented programming principles and abstract base classes. This version allows for clean game tracking, reusable logic, and an easy-to-extend structure.

## 👤 Player-Centric Gameplay

Each game session tracks:
- Player name
- Rounds played
- Wins and losses

Built around a flexible `Game` abstract base class, this Hangman implementation ensures future game types could be added easily by extending the base class.

## 🎮 Features

- 🎯 Random word selection from a built-in library
- 🧠 Intelligent letter guessing with tracking
- 🛑 Limited incorrect guesses (configurable)
- 📈 Game summaries for performance tracking
- 🔄 Option to replay rounds seamlessly
- 🧱 Clean code structure using inheritance and encapsulation

## 🧰 Technologies Used

- **Python 3**
- **OOP principles** (inheritance, abstraction, encapsulation)
- **ABC module** for enforcing consistent structure across game types

## 📋 How to Play

1. Clone the repository:
   ```bash
   git clone https://github.com/ArnesKapic/HangmanGame.git
   cd HangmanGame

