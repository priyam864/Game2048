# 2048 Game in Java

This is a simple implementation of the 2048 game using Java and Swing. The game involves merging tiles of the same value on a 4x4 grid to reach the 2048 tile.

## Features

- **Keyboard Controls**: 
  - Move tiles using arrow keys (`↑`, `↓`, `←`, `→`).
  - Additional controls with `W`, `A`, `S`, `D` keys for the same movements.
  - Press `ESC` to reset the game.
  
- **Responsive UI**: 
  - The game grid adjusts based on the player's moves.
  - Displays score and status (win or lose) in real-time.

- **Win/Lose Logic**: 
  - Win by creating the 2048 tile.
  - Lose if no more moves are possible.

- **Smooth Animations**: 
  - Visual feedback for merging and moving tiles.

## Technologies Used

- **Java**: Core logic implementation.
- **Swing**: GUI design and handling user interactions.
- **AWT**: Drawing components and rendering the game interface.

## How to Execute the Project

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/priyam864/Game2048.git
   ```
   
2. **Open the Project in an IDE**: 
   - Open the project folder in Visual Studio Code, IntelliJ IDEA, or Eclipse.

3. **Compile and Run**: 
   - Ensure you have a Java Development Kit (JDK) installed.
   - Run the `main` method in the `Game2048` class.

4. **Start Playing**: 
   - The game window will open, and you can start playing the 2048 game.

## How to Run the Game

- **Running via Command Line**:
  1. Navigate to the project directory.
  2. Compile the Java files:
     ```bash
     javac Game2048.java
     ```
  3. Run the compiled program:
     ```bash
     java Game2048
     ```

## Steps to Play the Game

1. **Game Objective**:
   - Combine tiles with the same number to reach the 2048 tile.
  
2. **Movement Controls**:
   - Use the arrow keys (`↑`, `↓`, `←`, `→`) to move the tiles in the respective direction.
   - Alternatively, you can use `W`, `A`, `S`, `D` keys for moving the tiles.

3. **Game Actions**:
   - When two tiles with the same number touch, they merge into one with the combined value.
   - Your score increases by the value of the new tile formed after a merge.

4. **Winning the Game**:
   - Create a tile with the number 2048 to win the game.
  
5. **Game Over**:
   - The game ends when no more moves are possible and you haven't reached the 2048 tile.

6. **Restart the Game**:
   - Press `ESC` to reset and start a new game.

---



