# Tic_Tac_Toe_Game
The Tic-Tac-Toe game is a simple two-player game where each player takes turns marking a 3x3 grid. The goal of the game is to be the first player to get three of their marks in a row (horizontally, vertically, or diagonally). If all nine squares are filled and no player has three in a row, the game results in a draw.

**Features:**
  Interactive Gameplay: The game allows two players to play against each other in real-time by clicking on the grid.
  Dynamic Interface: The game grid dynamically updates to show the current player's mark (X or O) and automatically switches turns.
  Winning Logic: The game checks for winning combinations after each move. It announces the winner if a player gets three in a row, or declares a draw if all squares are filled with no winner.
  Reset Option: After the game ends (either a win or a draw), players can reset the game and play again without refreshing the page.
  Technologies Used:
  HTML: Provides the basic structure of the grid and the layout for the game.
  CSS: Styles the grid, giving it a clean and modern appearance. The CSS also handles hover effects and visual cues for player turns.
  JavaScript: Manages the game logic, handles player interactions, checks for winners, and updates the UI dynamically.
  Code Structure:
**HTML:**

  Creates a 3x3 grid using a simple <div> structure.
  Displays messages like player turns, win announcements, and draw results.
  Includes a "Reset" button to restart the game.
**CSS:**

  Styles the grid layout, aligning the gameboard.
  Provides visual feedback when a player hovers over or selects a grid square.
  Displays winning or drawing conditions with dynamic color changes.
**JavaScript:**
  
  Handles player moves, alternates between X and O.
  Implements logic to check for winning conditions or a tie.
  Updates the grid based on player interaction and announces the game result.
  Resets the game when players choose to start over.

  
