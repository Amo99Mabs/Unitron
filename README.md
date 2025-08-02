# 🎮 UNITRON - Number Guessing Game

Welcome to **UNITRON**, a simple yet engaging number guessing game built with Python! Test your intuition and logic as you try to guess the secret number randomly selected between 1 and 100.

---

## 🚀 Features

- 🔢 Random number generation using `random.randint`
- 🧠 Input validation to ensure guesses are within range
- 📈 Tracks number of attempts
- 💬 Feedback on each guess: too high, too low, or correct
- 🛑 Ends game when the correct number is guessed

---

## 🐞 Known Issues

- ❗ The "Too high" condition is currently duplicated and needs correction:
  ```python
  elif guess < answer:  # This should be elif guess > answer
