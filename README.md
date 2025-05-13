# 🐍 Snake Game

A classic Snake Game built with **HTML**, **CSS**, and **JavaScript**. The goal is simple — eat the food, grow your snake, and try not to collide with yourself!

---

## 🚀 Live Demo

You can run the game by simply opening the `index.html` file in any modern web browser.

---

## 🕹️ How to Play

Use the arrow keys on your keyboard to move the snake:

* `↑` Up
* `↓` Down
* `←` Left
* `→` Right

🎯 **Goal**:

* Eat the red square (food) to grow and increase your score.
* Every 50 points, the level increases and the game speed gets faster.
* Avoid colliding with yourself — or the game will reset!

---

## 📦 Features

* 🎮 Responsive 400x400 game canvas
* ⏩ Increasing difficulty based on score
* 📈 Score and level tracking
* 🔄 Snake wraps around the screen (no wall collisions)
* 🧼 Clean UI with simple controls

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Vanilla JavaScript**

---

## 📁 Project Structure

```
snake-game/
├── index.html       # Main game file
└── README.md        # Project documentation
```

---

## 🔧 Customization

You can tweak game settings in the JavaScript code:

* `gridSize` – Size of each square tile
* `tileCount` – Number of tiles (calculated from canvas width / gridSize)
* Speed adjustment:

  ```js
  setTimeout(gameLoop, 1000 / (10 + level));
  ```

  Change the `10` or `level` logic to customize speed progression

---

## 🧠 Future Improvements

* 🔊 Add sound effects and animations
* ☠️ Show a "Game Over" message before reset
* 🏆 Add a high score feature
* 📱 Add touch controls for mobile devices

---

## 📜 License

This project is open-source and free to use under the [MIT License](https://opensource.org/licenses/MIT).

---

