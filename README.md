# Java-Snake-Game

This is a simple **Snake Game** developed in Java using `Swing` for the graphical user interface (GUI). The game involves controlling a snake that moves around the screen, consuming cherries to grow in size. The player scores points by eating cherries, and the game ends if the snake collides with the walls or its own body.

### Key Features:

- **Snake Movement**: Control the snake using the arrow keys (`Up`, `Down`, `Left`, `Right`).
- **Cherries**: The snake earns points by consuming randomly spawned cherries.
- **Pause/Resume**: The game can be paused or resumed using the `P` key.
- **Game Over**: The game ends if the snake hits the wall or itself, and the player can restart by pressing the `Enter` key.
- **Best Score Tracking**: The game tracks and displays the best score achieved.

### Game Mechanics:

- **Snake**: 
  - The snake moves in four directions and grows in length every time it consumes a cherry.
  - Movement is handled by updating the position of the snake's head and its body (tail).
  
- **Cherries**: 
  - Randomly spawned on the game field. The snake earns points by "eating" cherries, which are represented as images or simple colored circles.
  
- **Collision Detection**: 
  - The game checks if the snake hits the walls or its own body, triggering the game over state.

### Controls:

- **Arrow Keys**: Control snake's movement.
- **Enter**: Restart the game after a game over.
- **P**: Pause or resume the game.

### Technologies Used:

- **Java Swing**: For building the graphical user interface and rendering game elements like the snake and cherries.
- **Timer**: The game loop is implemented using a `Timer` to update and redraw the game elements at regular intervals.
- **BufferedImage**: Used to display the cherry image when available.

### How to Run:

1. Clone or download the repository.
2. Compile and run the Java files using any IDE (like IntelliJ, Eclipse) or through the command line.
3. Use the arrow keys to control the snake and enjoy the game!
