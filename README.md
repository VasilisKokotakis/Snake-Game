
---

# 🐍 Snake Game

A simple **Snake Game** built with Python's `turtle` module.
The game features score tracking, high score persistence, and smooth snake movement.

---

## 🎮 How to Play

* Use the **arrow keys** (`Up`, `Down`, `Left`, `Right`) to control the snake.
* Eat the **blue food** to grow your snake and increase your score.
* Avoid:

  * Hitting the **walls**.
  * Running into your **own tail**.
* The game automatically resets when you collide, but your **high score** is saved in `data.txt`.

---

## 📂 Project Structure

```
snake-game/
│── main.py         # Entry point of the game
│── snake.py        # Snake class (movement, growth, reset)
│── food.py         # Food class (random spawn, refresh)
│── scoreboard.py   # Scoreboard with high score persistence
│── data.txt        # Stores high score (created automatically if missing)
```

---

## 🚀 How to Run

1. Make sure you have **Python 3.7+** installed.
2. Clone or download this repository.
3. Run the game with:

   ```bash
   python main.py
   ```

---

## 🛠 Features

* 🐍 Smooth snake movement
* 🍎 Random food spawning
* 🏆 High score tracking (stored in `data.txt`)
* 🔄 Auto-reset after collisions

---

## 📖 Requirements

* No external libraries needed.
* Uses only Python’s **built-in `turtle` and `random` modules**.

---

## 🌟 Future Improvements (Ideas)

* Add difficulty levels (increasing speed over time).
* Add sound effects.
* Add a start/restart menu.
* Track and display average session scores.

---

