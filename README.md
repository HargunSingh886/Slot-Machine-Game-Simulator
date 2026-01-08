# 🎰 Python Slot Machine Game

A simple command-line slot machine game built using Python.
Deposit money, place bets, spin the machine, and test your luck.

No external libraries. Just Python and probability pretending to be fair.

---

## 🧠 How the Game Works

1. Deposit money to start playing
2. Choose:
   - Number of lines to bet on (1–3)
   - Bet amount per line
3. A 3×3 slot grid is generated randomly
4. Matching symbols across a line win money
5. Your balance updates after each spin
6. Play until you quit or run out of funds

---

## 🎯 Slot Machine Rules

- 3 rows × 3 columns
- Maximum of 3 betting lines
- Each symbol has a probability of appearing and a payout value

---

## 🔣 Symbols & Payouts

| Symbol | Frequency   | Payout |
| ------ | ----------- | ------ |
| A      | Rare        | 5× bet |
| B      | Medium      | 4× bet |
| C      | Common      | 3× bet |
| D      | Very Common | 2× bet |

Rare symbols appear less often but reward more.

---

## 💰 Betting Rules

- Minimum bet per line: ₹1
- Maximum bet per line: ₹100
- Total Bet = Bet per Line × Number of Lines

You cannot bet more than your current balance.

---

## ▶️ Example Output

    A | B | C
    D | D | B
    C | A | D

    You won ₹20.
    Winning lines: 2

---

## 🛠️ How to Run

1. Ensure Python 3 is installed
2. Save the game file as `slot_machine.py`
3. Run the program using:

   python slot_machine.py

---

## 📁 Project Structure

    slot_machine.py
    README.md

Everything is intentionally kept in one file for simplicity.

---

## 🚀 Why This Project?

This project is useful for:

- Practicing Python basics
- Understanding loops and functions
- Working with randomness
- Learning input validation
- Building a complete mini-game

---

## 🧩 Possible Improvements

- Add diagonal winning lines
- Convert to Object-Oriented Programming
- Add colors or animations
- Create a GUI or web version
- Save balance between sessions

---

## 📜 License

Free to use, modify, and improve.
If you lose money in this game, that’s on you.
