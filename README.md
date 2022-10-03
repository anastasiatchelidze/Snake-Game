# Snake-Game

classic snake game where the player uses the arrow keys to move the snake across the screen. Food for snake is randomly generated on the screen and appears at different place every time after snake eats it. Eating food makes snake longer (by adding new segments - new turtle object with the shape of square) and it also increases the score by 1 each time.

If snake collides with the wall or its own tail, game will be over. When the game ends, the score is compared with the high score obtained from previous games and saved in the .txt file. If it's higher than current high score, than new score is stored instead. At the beginning of the game, both: current score and high score is shown on the screen so user can keep track of them throughout the game.
