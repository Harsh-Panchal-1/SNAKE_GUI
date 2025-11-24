Snake Game (Java Swing)

A simple and classic Snake Game implemented using Java, Swing, and AWT libraries. The project renders a playable snake game inside a JPanel, complete with movement, collision detection, scoring, and a game-over screen.


---

🎮 Features

Smooth snake movement using arrow keys

Randomly generated food

Score tracking

Collision detection (walls + snake body)

Clean UI using Graphics

Adjustable speed via DELAY



---

🧱 How the Game Works

The snake moves automatically based on the last direction pressed.

Eating food increases the snake's body length and score.

Hitting a wall or the snake's own body ends the game.



---

🧩 File Structure

SnakeGame.java

Contains everything:

Game window setup

Snake movement

Food spawning

Collision checks

Rendering logic



---

🚀 How to Run the Game

1. Install Java JDK 8+.


2. Save the file as: SnakeGame.java.


3. Compile the code:



javac SnakeGame.java

4. Run the game:



java SnakeGame

A game window will appear. Use arrow keys to play.


---

🛠️ Controls

Key	Action

⬅️	Move Left
➡️	Move Right
⬆️	Move Up
⬇️	Move Down



---

📌 Code Highlights

Game Loop

Uses a Swing Timer to update movement and rendering.

Collision Mechanics

Wall detection using coordinate boundaries

Self-collision using body array checks


Rendering

Snake head: Red

Snake body: Black

Food: Green

Score Display: Yellow text



---

📸 Screens You Will See

Gameplay screen with live score

Game Over screen with final score displayed



---

⭐ Future Improvements (Optional)

Add restart option

Add levels or increasing speed

Add background music

Add high-score storage



---

🧑‍💻 Author

A simple classic Snake Game built using core Java — perfect for learning GUI programming, game loops, and event handling.


---

📄 License

Feel free to use, modify, and learn from the code.
