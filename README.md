Candy Blitz - Premium Ultra

A high-performance, arcade-style Match-3 puzzle game built with Vanilla JavaScript. This project demonstrates advanced DOM manipulation, recursive logic, and the HTML5 Drag and Drop API.

Technical Features

1. Game Engine & Logic

Vanilla JS Core: Built without external libraries or game engines, ensuring a lightweight footprint and 100% control over the game loop.

Recursive Match Detection: Implements a scanning algorithm to detect horizontal and vertical matches of 3 or more elements.

Board Gravity: A custom "Move Down" system that shifts existing candies and generates new ones to fill empty slots using asynchronous delays.

2. User Experience (HCI)

Dual Game Modes: Includes Timed Mode for competitive play and Endless Mode for relaxed gameplay.

Responsive Particle System: A dynamic feedback loop that generates CSS-based particle bursts at the coordinate of every match.

Cross-Platform Support: Integrated Touch events for mobile compatibility alongside standard mouse Drag & Drop.

3. Persistence & Performance

State Management: Uses LocalStorage to persist high scores across browser sessions.

Optimized Animations: Leverages CSS3 hardware acceleration (GPU) for smooth 60fps animations, including the background "sparkles" and neon glow effects.

🛠️ Tech Stack

Language: JavaScript (ES6+)

Markup: HTML5

Styling: CSS3 (Flexbox, Grid, Animations, Radial Gradients)

Fonts: Fredoka One (via Google Fonts)

Project Structure

├── index.html      # Main entry point and game structure

├── style.css       # Neon-themed UI and particle animations

├── script.js       # Game logic, match detection, and gravity

└── README.md       # Project documentation
