# 3D Tic-Tac-Toe

A modern, interactive 3D Tic-Tac-Toe game built with Three.js, featuring smooth animations, orbital camera controls, and an immersive gaming experience.

## Features

- **3D Gameplay**: Fully rendered 3D board with crosses and circles
- **Smooth Animations**: Objects scale up with smooth animations when placed or revealed
- **Interactive Controls**: Click to place pieces and orbit around the board
- **Win Detection**: Automatic detection of winning conditions with visual strike-through lines
- **Responsive Design**: Adapts to different screen sizes
- **Modern Graphics**: Uses Three.js WebGL renderer with anti-aliasing and shadows

## Demo

The game features:
- A 3×3 grid rendered in 3D space
- Alternating turns between X (crosses) and O (circles)
- Smooth scaling animations for all game elements
- Visual win indicators with strike-through lines
- Orbital camera controls to view the board from any angle

## Technologies Used

- **Three.js**: 3D graphics library for WebGL rendering
- **JavaScript ES6+**: Modern JavaScript with classes and modules
- **CSS**: Styling and layout
- **HTML5**: Canvas element for WebGL rendering

## Project Structure

```
├── main.js          # Main application entry point
├── style.css        # Styling and layout
└── index.html       # HTML template with canvas element
```

## Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd 3d-tic-tac-toe
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Open your browser** and navigate to `http://localhost:5173`


## How to Play

1. **Launch the game** - The 3D board will animate into view
2. **Click on any square** to place your piece (starts with O)
3. **Players alternate** between O (circles) and X (crosses)
4. **Orbit around the board** by dragging with your mouse
5. **Win conditions**: Get three in a row horizontally, vertically, or diagonally
6. **Win indicator**: A colored strike-through line will appear when someone wins

### Key Features
- **Raycasting**: Detects mouse clicks on invisible tiles
- **Animation System**: Smooth scaling animations for all objects
- **Modular Design**: Clean separation between game logic and 3D rendering
- **Responsive**: Automatically adjusts to window resize

Win conditions check:
- **Rows**: Horizontal three-in-a-row
- **Columns**: Vertical three-in-a-row  
- **Diagonals**: Both diagonal directions
