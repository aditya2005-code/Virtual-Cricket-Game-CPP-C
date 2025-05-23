
I completed this project as part of my C and C++ Programming Course on Internshala. It helped me strengthen my understanding of C++ syntax, class structure, dynamic memory, and real-time logic simulation.

# Virtual Cricket Game 🎮🏏

This is a simple terminal-based **Virtual Cricket Game** implemented in **C++**. The game allows users to form two teams from a pool of players, toss a coin, and simulate a short cricket match (6-ball innings). It demonstrates object-oriented programming concepts using classes and basic game logic.

---

## 🧑‍💻 Project Overview

### Features:
- Pool of 11 real-world cricket players.
- Team selection (4 players each).
- Toss simulation with choice to bat or bowl.
- 6-ball innings for each team.
- Basic scorecard and match progression.
- Command-line based interaction.

### Technologies Used:
- **C++** (Object-Oriented Programming)
- **Standard Template Library (STL)** for vectors and input handling
- **Modular design** with multiple header and source files

---

## 📂 File Structure

Virtual-Cricket-Game/
│
├── Virtual-Game.cpp # Main file
├── game.cpp # Game logic implementation
├── game.h # Game class declaration
├── team.cpp # Team class implementation
├── team.h # Team class declaration
├── player.cpp # Player class implementation
├── player.h # Player class declaration
├── README.md # Project documentation


---

## ⚙️ How to Run

Make sure all `.cpp` and `.h` files are in the same directory. Then compile and run with:

```bash
g++ Virtual-Game.cpp game.cpp team.cpp player.cpp -o VirtualGame
./VirtualGame

Welcome to Virtual Cricket Game!
Instructions:
1. Create 2 teams of 4 players each.
2. Toss to choose to bat or bowl.
3. Play 6-ball innings per team.
4. View the scorecard and winner!
