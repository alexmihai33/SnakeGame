Snake game rules: you control a snake with w,a,s and d (w is up, a is left, s down, d right). You need to collect food (appearing as little blue dots on the screen) in order to get bigger (add new segments to your body). If you touch the edge of the screen or your tail you lose.

This is a snake game made with python and turtle GUI. The project has 4 classes:

1. food: it defines and spawns the little dots that the snake has to eat to get bigger
2. scoreboard: this is where everything that is written is made (the scoreboard in the game + updating that everytime the snake eats and a simple game over text when you lose)
3. snake: this is where snake is created (it first starts as 3 turtle objects - 3 squares united), where adding new segments to the snake is defined as a method and where methods are created for snake's movement.
4. main: where we initalise our screen, make objects for every class mentioned above, create a loop in which the game plays, and deal with the main game events: collecting the food and losing the game.
