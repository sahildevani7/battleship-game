# Battleship Game

A real-time multiplayer Battleship game implementation using Node.js, Express, and Socket.IO.

## Demo

https://github.com/user-attachments/assets/6f6a17b1-f4e1-4e19-ae7b-9969848f55de

[Project Report](Report.pdf)

## Features

- Real-time two-player gameplay
- Drag and drop ship placement
- Socket.IO for real-time communication
- Responsive design
- Player connection status indicators
- Game state management

## Technologies Used

- Node.js
- Express
- Socket.IO
- HTML5
- CSS3
- JavaScript (Vanilla)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/battleship-game.git
   cd battleship-game
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   npm start
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## How to Play

1. Open the game on two different browser tabs 
2. Click "Connect" to join the game
3. Drag and place your ships on your grid
4. Click "Start" when ready
5. Take turns firing at your opponent's grid
6. Sink all enemy ships to win!

## Game Rules

- Each player has 5 ships of different lengths:
  - Carrier (5 cells)
  - Battleship (4 cells)
  - Cruiser (3 cells)
  - Submarine (3 cells)
  - Destroyer (2 cells)
- Players take turns shooting at the opponent's grid
- A hit is marked in red, a miss in white
- The first player to sink all enemy ships wins
