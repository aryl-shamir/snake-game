# snake-game
Classic Snake Game using Python and Turtle

# 🐍 Snake Game with Python Turtle

This is a simple Snake Game project built using Python and the Turtle graphics module. The project was created step by step using basic concepts of Object-Oriented Programming and game development.

---

## 🚧 Step-by-Step Project Build

### ✅ TODO 1: Create a Snake Body
- I started by creating a `Snake` class in `snake.py`.
- The snake was made from square turtle objects placed next to each other.
- I used a list to store each part of the snake.

### ✅ TODO 2: Move the Snake
- I made the snake move by looping from the tail to the head.
- Each segment moves to the position of the segment in front of it.
- The head moves forward by a fixed distance using `.forward()`.

### ✅ TODO 3: Control the Snake
- I added control using the arrow keys.
- The methods `up()`, `down()`, `left()`, and `right()` change the direction of the head.
- The `onkey()` method in `main.py` was used to link keypresses to snake movement.

### ✅ TODO 4: Detect Collision with Food
- I created a `Food` class in `food.py` using a small circle turtle object.
- When the head gets close to the food, it disappears and reappears in a new random location.
- The snake also grows longer by adding a new segment.

### ✅ TODO 5: Create a Scoreboard
- I created a `Scoreboard` class in `scoreboard.py`.
- It keeps track of the current score.
- Each time the food is eaten, the score increases and is updated on the screen.

### ✅ TODO 6: Detect Collision with Wall
- I checked the snake's head position.
- If it goes beyond the screen limit (±290), the game stops and "Game Over" is displayed.

### ✅ TODO 7: Detect Collision with Tail
- I looped through each segment of the snake (except the head).
- If the head touches any part of the body, the game ends.

---

## 🕹 How to Play

- Run the game with `python main.py`.
- Use **Arrow Keys** to control the snake:
  - Up = ↑
  - Down = ↓
  - Left = ←
  - Right = →
- Eat the food to grow and increase your score.
- Don’t touch the walls or your own tail!

---

## 📁 Files in This Project


snake-game/
├── main.py # Main game loop
├── snake.py # Snake class and movement
├── food.py # Food class and behavior
├── scoreboard.py # Score display and game over
└── README.md # Instructions and explanation

# what i learned 
- How to use Python's Turtle module
- Basics of game development
- Object-oriented programming (classes and methods)
- Handling user input and collision detection

Thanks for reading
