
# 2048 Game

A fully functional implementation of the classic 2048 puzzle game built with vanilla JavaScript, demonstrating advanced DOM manipulation, object-oriented programming, and modern web development practices.

## 🎮 [Live Demo](https://CNegruzzi.github.io/2048-game/)

## 📋 Overview

This project showcases my proficiency in:
- **JavaScript ES6+**: Object-oriented programming with classes, array manipulation, and algorithm implementation
- **DOM Manipulation**: Dynamic content updates, event handling, and responsive user interactions
- **SCSS/CSS**: Advanced styling, grid layouts, and responsive design
- **Game Logic**: Complex state management, collision detection, and scoring algorithms
- **User Experience**: Smooth animations, keyboard controls, and intuitive interface design

## ✨ Features

- **Classic 2048 Gameplay**: Slide tiles to combine numbers and reach the 2048 tile
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Keyboard Controls**: Arrow keys for seamless gameplay
- **Smart Game Logic**:
  - Proper tile merging with anti-double-merge protection
  - Random tile generation (90% chance for 2, 10% chance for 4)
  - Win/lose condition detection
- **Dynamic Scoring**: Real-time score calculation based on merged tile values
- **Game State Management**: Start, restart, and continue functionality
- **Visual Feedback**: Color-coded tiles and smooth animations

## 🛠 Technical Implementation

### Core Architecture
- **Modular Design**: Separation of game logic (`Game.class.js`) and UI rendering (`main.js`)
- **Class-Based Structure**: Clean OOP implementation with well-defined methods
- **State Management**: Immutable game state handling for reliable gameplay

### Key Methods Implemented
```javascript
// Core game mechanics
constructor(initialState)  // Initialize game board
getState()                // Return current board state
getScore()               // Return current score
getStatus()              // Return game status (idle/playing/win/lose)

// Movement logic
moveLeft(), moveRight(), moveUp(), moveDown()  // Handle directional moves

// Game control
start()                  // Begin new game
restart()               // Reset to initial state
```

### Algorithm Highlights
- **Tile Movement**: Efficient array manipulation for sliding tiles in any direction
- **Merge Detection**: Smart algorithm preventing double-merges in single moves
- **Random Generation**: Weighted probability system for new tile placement
- **Win/Lose Logic**: Comprehensive game state evaluation

## 🎯 Game Rules

1. **Objective**: Combine tiles to create the 2048 tile
2. **Movement**: Use arrow keys to slide all tiles in chosen direction
3. **Merging**: Identical adjacent tiles combine into their sum
4. **Scoring**: Points awarded equal to the value of merged tiles
5. **Victory**: Achieve the 2048 tile to win
6. **Game Over**: No valid moves remaining

## 🚀 Getting Started

### Prerequisites
- Node.js (for development and testing)
- Modern web browser with ES6+ support

### Installation
```bash
# Clone the repository
git clone https://github.com/CNegruzzi/js_2048_game.git

# Navigate to project directory
cd js_2048_game

# Install dependencies
npm install
```

### Development
```bash
# Run tests
npm run test

# Run quick tests (skip linter)
npm run test:only -- -n

# Run tests with detailed console output
npm run test:only -- -l
```

### Deployment
The game is deployed using GitHub Pages and automatically updates with new commits to the main branch.

## 🏗 Project Structure

```
src/
├── modules/
│   └── Game.class.js     # Core game logic and algorithms
├── styles/
│   └── main.scss         # SCSS styling with modern design
├── scripts/
│   └── main.js           # DOM manipulation and UI handling
└── index.html            # Semantic HTML structure
```

## 🔧 Technical Skills Demonstrated

- **JavaScript Proficiency**: Advanced array methods, object manipulation, algorithm design
- **DOM Expertise**: Event delegation, dynamic content updates, performance optimization
- **CSS/SCSS Mastery**: Grid layouts, animations, responsive design principles
- **Code Organization**: Modular architecture, clean code practices, maintainable structure
- **Testing**: Unit test compatibility and debugging capabilities
- **Version Control**: Git workflow and professional project management

## 🎨 Design Decisions

- **Minimal Dependencies**: Vanilla JavaScript implementation showcasing core language skills
- **Performance Focused**: Efficient algorithms for smooth 60fps gameplay
- **Accessibility**: Keyboard navigation and clear visual hierarchy
- **Mobile Responsive**: Touch-friendly interface scaling across devices

## 🔍 Code Quality

This project demonstrates:
- Clean, readable code with consistent formatting
- Comprehensive error handling and edge case management
- Efficient algorithms with optimal time complexity
- Proper separation of concerns between logic and presentation
- Test-driven development approach compatibility

## 🤝 Contributing

This is a portfolio project, but feedback and suggestions are always welcome! Feel free to open issues or reach out with any questions about the implementation.

---

*This project demonstrates my ability to build complex, interactive web applications using modern JavaScript practices and showcases my understanding of game development principles, algorithm design, and user experience optimization.*
