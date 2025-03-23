Arduino code is located in src.

In this fast-paced two-player game, two ships engage in an intense laser battle to score as many points as possible before time runs out.

The game starts with a menu displaying brief instructions. Turning either encoder will begin the match.

Controls:

- Each player controls a ship using their respective encoder.

- Rotating the encoder clockwise moves the ship right, while rotating it counterclockwise moves it left.

- Pressing the encoder fires a laser. There is a shot cooldown that prevents spamming.

Gameplay:

- Hitting the opponent's ship earns you a point.

- A moving mirror in the center of the screen reflects lasers. Hitting the mirror will award a point to your opponent.

- Each player’s score is displayed at the bottom of the screen.

- A 60-second timer counts down.

Winning & Restarting:

- When the timer reaches zero, the player with the most points wins, and the game moves to the restart menu displaying the winner’s color.

- Clicking either encoder restarts the game.

- If both players have the same score, the game automatically resets for another round.