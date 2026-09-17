# Leap Runner

<div align="center"><img src="preview.png" width="1920" height="1080" /></div>

A fast-paced 2D side-scrolling endless runner built with pure HTML5 Canvas and vanilla JavaScript.

Dodge enemies, jump over obstacles, and see how high you can score!

## How to Play

### Desktop (Keyboard)

| Action         | Key                           |
| -------------- | ----------------------------- |
| Move Left      | ← Left Arrow                  |
| Move Right     | → Right Arrow                 |
| Jump           | ↑ Up Arrow                    |
| Pause / Resume | **P** or **Space** or **Esc** |
| Restart        | Enter (after Game Over)       |
| Fullscreen     | Click the Fullscreen button   |

### Mobile (Touch)

| Action         | Gesture / Control                     |
| -------------- | ------------------------------------- |
| Move Left      | Touch & hold **left half** of screen  |
| Move Right     | Touch & hold **right half** of screen |
| Jump           | **Swipe up**                          |
| Pause / Resume | Tap the **Pause** button              |
| Restart        | **Swipe down** (after Game Over)      |

> **Important:** Play in **landscape** mode.  
> The game will show a “Please rotate your phone” screen if you are in portrait.

## Features

- 5-second countdown before the game starts
- Pause / Resume (keyboard + on-screen button)
- Smooth sprite-sheet animation for player and enemies
- Collision detection
- Score tracking
- Full touch controls for mobile (left / right / jump)
- Fullscreen support
- Portrait-mode lock with animated rotate prompt
- Responsive canvas

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/leap-runner.git
   cd leap-runner
   ```

2. Open `index.html` in a modern browser  
   _(or serve it with any static file server)_

   ```bash
   # Example with Python
   python -m http.server 8000
   ```

3. Play!

## Project Structure

```
leap-runner/
├── index.html          # Main HTML
├── style.css           # Styles + rotate overlay + UI buttons
├── script.js           # Game logic
├── player.png          # Player sprite sheet
├── enemy_1.png         # Enemy sprite sheet
├── background_single.png
└── README.md
```

## Browser Support

Works best in modern browsers that support:

- HTML5 Canvas
- ES6+
- Fullscreen API
- Touch events / Orientation media queries

## Credits

Built with vanilla JavaScript.  
Sprite assets included in the project.

---

Enjoy the run! 🏃‍♂️
