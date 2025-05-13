🐍 Snake Game
    A classic Snake Game built with HTML, CSS, and JavaScript. The goal is simple — eat the food, grow your snake, and try not to collide with yourself!

🚀 Live Demo
    You can run the game by simply opening the index.html file in any modern web browser.

🕹️ How to Play
    Use the arrow keys on your keyboard to move the snake:
    
    ↑ Up
    
    ↓ Down
    
    ← Left
    
    → Right

    Eat the red square (food) to grow and increase your score.
    
    Every 50 points, the level increases, and the game speed gets faster.
    
    Don't let the snake collide with itself — or the game will reset!

📦 Features
    Responsive 400x400 game canvas.
    
    Increasing difficulty based on score.
    
    Score and level tracking.
    
    Snake wraps around the screen (no wall collisions).
    
    Clean UI with simple game controls.

🛠️ Technologies Used
    HTML5
    
    CSS3
    
    JavaScript (Vanilla)

📁 Project Structure
    bash
    Copy
    Edit
    snake-game/
    ├── index.html       # Main game file
    └── README.md        # Project documentation
🔧 Customization
    You can tweak the following game settings in the JavaScript section:

    gridSize - Size of each square tile.

    tileCount - Number of tiles in the game (auto-calculated).

    Speed adjustment: setTimeout(gameLoop, 1000 / (10 + level)); — Increase base speed or change increment logic.


🧠 Future Improvements
    Add sound effects and animations.

    Display a "Game Over" message instead of instantly resetting.
    
    Add a high score feature.

    Add touch controls for mobile devices.

📜 License
    This project is open-source and free to use.
