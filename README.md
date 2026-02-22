# 🐍 Snake, Water, Gun Game in C

A simple **C program** that lets you play the classic **Snake-Water-Gun** game against the computer!  
It uses random number generation to simulate the computer's choice.

---

## 🎮 How to Play

1. The game presents you with three choices:
   - `0` → Snake  
   - `1` → Water  
   - `2` → Gun  

2. You’ll input your choice.  
3. The computer will randomly pick one of the three options.  
4. The winner is decided based on the rules below.

---

## 🧩 Game Rules

| Player Choice | Computer Choice | Result         |
|----------------|----------------|----------------|
| Snake (0)      | Water (1)      | 🏆 You Win!     |
| Snake (0)      | Gun (2)        | ❌ You Lose!    |
| Water (1)      | Gun (2)        | 🏆 You Win!     |
| Water (1)      | Snake (0)      | ❌ You Lose!    |
| Gun (2)        | Snake (0)      | 🏆 You Win!     |
| Gun (2)        | Water (1)      | ❌ You Lose!    |
| Any same choice | Any same choice | 🤝 Draw!        |

---

## ⚙️ How It Works

- The program uses:
  - `rand()` to generate a random number for the computer's choice.
  - `srand(time(0))` to ensure randomness every time the program runs.
- Based on both choices, it prints whether **you win, lose, or draw**.

---

## 🚀 How to Run

1. **Compile the code** using a C compiler:
   ```bash
   gcc snake_water_gun.c -o game


Example Output
Choose 0 for Snake, 1 for water and 2 for Gun
1
Computer chose 0
You Lose!

💡 Notes

Make sure to enter a valid number (0, 1, or 2), otherwise you’ll get the message:

Something went wrong!


Each run gives a different computer choice thanks to the use of time(0) in randomization.

🧑‍💻 Author

Aradhya Negi

Simple and fun mini-project in C to practice conditionals and randomization 🎲


---

Would you like me to make it a bit more **fun and stylish** with emojis and formatting (like a GitHub-friendly project readme), or keep it **professional and minimal** for college submission?
