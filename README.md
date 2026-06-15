# 🐍 AI-Nibbles

A classic Snake game built with vanilla HTML5, CSS, and JavaScript. Navigate your snake, eat food, and avoid collisions in this retro-styled arcade game!

## 🎮 Game Overview

AI-Nibbles is a web-based implementation of the timeless Nibbles (Snake) game with a sleek, retro aesthetic. The game features a neon green on black color scheme reminiscent of classic arcade games.

## 🚀 Features

- **Classic Gameplay**: Navigate your snake to eat food and grow longer
- **Score Tracking**: Keep track of your score as you progress
- **Collision Detection**: Game ends when you hit walls or yourself
- **Responsive Controls**: Use arrow keys or WASD for smooth movement
- **Retro Aesthetic**: Neon green graphics with classic arcade styling
- **Game Over Screen**: Press SPACE to restart after game ends
- **Self-Collision Prevention**: Prevents the snake from moving backward into itself

## 🎯 How to Play

1. **Start the Game**: Open `index.html` in your web browser
2. **Move the Snake**: 
   - Use **Arrow Keys** (↑ ↓ ← →) OR
   - Use **WASD Keys** (W A S D)
3. **Eat Food**: Move your snake's head over the red food squares to grow
4. **Avoid Collisions**: 
   - Don't hit the walls (canvas borders)
   - Don't run into your own body
5. **Game Over**: When you collide, press **SPACE** to restart

## 📊 Scoring

- **Points**: Each food eaten = **10 points**
- **Goal**: Achieve the highest score possible!

## 🛠️ Technical Details

### Technologies Used
- **HTML5**: Game structure and canvas
- **CSS3**: Styling and visual effects
- **JavaScript (Vanilla)**: Game logic and mechanics

### Game Mechanics
- Grid-based movement system (20x20 pixel tiles on 400x400 canvas)
- 100ms game update interval for consistent gameplay
- Anti-aliasing with direction change queuing to prevent accidental self-collision
- Random food generation with validation (food never spawns on the snake)

### Key Functions
- `update()`: Main game loop
- `moveSnake()`: Handles snake movement and food collision
- `drawSnake()`: Renders the snake on canvas
- `drawFood()`: Renders food items
- `hasGameEnded()`: Checks for collision conditions
- `handleKeyPress()`: Processes player input

## 📁 Project Structure

```
AI-Nibbles/
├── index.html    # Main game file (HTML + CSS + JavaScript)
└── README.md     # This file
```

## 🎨 Visual Design

- **Background**: Dark (#1a1a1a) with neon green text
- **Snake Head**: Bright green (#00ff00)
- **Snake Body**: Darker green (#00aa00)
- **Food**: Red (#ff3333)
- **Canvas Border**: Glowing green with shadow effect
- **Font**: Monospace (Courier New) for retro feel

## 🚦 Game States

1. **Playing**: Snake is moving and responding to input
2. **Game Over**: Collision detected, displays "GAME OVER" message
3. **Restart**: Press SPACE to reset and play again

## 💡 Tips & Tricks

- **Plan Ahead**: Think about your snake's path to avoid dead ends
- **Use Both Controls**: Familiarize yourself with arrow keys and WASD
- **Be Patient**: The game updates every 100ms - time your moves carefully
- **Practice**: Master the controls to achieve high scores

## 🔮 Future Enhancements

Possible features for future versions:
- Difficulty levels with adjustable game speed
- High score persistence using localStorage
- Sound effects and background music
- Power-ups and obstacles
- Multiplayer mode
- Different game modes (endless, time attack, etc.)

## 📝 License

This project is open source and available for anyone to use and modify.

## 🤝 Contributing

Feel free to fork this repository, make improvements, and submit pull requests!

## 🎓 Learning Resource

This project is a great example for beginners learning:
- HTML5 Canvas API
- Game development concepts
- Event handling in JavaScript
- Game loops and state management

---

**Enjoy the game! 🎮 Try to beat your high score!**
