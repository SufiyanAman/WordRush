# 🔤 WordRush - DSA Project

This is a Python word game built using Tkinter for the interface and a Trie data structure for efficient word lookup. It was developed as a course project for the Data Structures and Algorithms (DSA) course.

---

## 🧠 Why We Used a Trie

We used a **Trie** (prefix tree) to store and search dictionary words because it offers:

- 🔍 **Fast lookup**: Searching whether a word exists is much faster than in a normal list — especially useful when you have thousands of words.
- 🌳 **Efficient structure**: It saves space by sharing prefixes between words.
- 💡 **Great for word games**: Tries are commonly used in autocomplete, word puzzles, and spell checkers.

This made it the perfect choice for our word game, where quick and repeated word validation is needed during gameplay.

---

## 🎮 How the Game Works

- You're given **10 random letters**
- Use those letters to make valid English words
- Rules:
  - The word must only use the given letters
  - It must be a real English word (from `words.txt`)
  - You can't repeat the same word
- You earn points based on word length
- Each valid word adds extra time to the countdown

---

## ▶️ How to Run

1. Make sure Python is installed
2. Add a `words.txt` file in the same folder (one word per line)
3. Run the game:
   ```bash
   python main.py
