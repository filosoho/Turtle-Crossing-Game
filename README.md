# Turtle Crossing Game
This is a simple turtle crossing game implemented in Python using the Turtle graphics library. The game involves a turtle trying to cross a road filled with moving cars to reach the other side safely.

# How to Play
Run the:
~~~
main.py
~~~
to start the game.  

* Use the Up arrow key to move the turtle upwards and try to cross the road without getting hit by the cars.  
* The game level increases as you successfully cross the road, making the cars move faster.  
* If the turtle collides with a car, the game ends and "GAME OVER" is displayed on the screen.  
* You can restart the game by running the turtle_crossing.py file again.  

# Dependencies
This game requires:
~~~
turtle library
~~~
which is a standard Python library for turtle graphics, to be installed.

# Files
The game consists of the following files:
~~~
main.py: The main game file that sets up:
the game window, initializes the player turtle, car manager, and scoreboard, and handles the game logic.  
~~~
~~~
player.py: Contains the Player class that represents the turtle player in the game.  
~~~
~~~
car_manager.py: Contains the CarManager class that manages the creation, movement, and level-up of the cars in the game.  
~~~
~~~
scoreboard.py: Contains the Scoreboard class that displays the current level and game over messages on the screen.  
~~~

# Classes


**Player**   

Represents the turtle player in the game. It has the following methods:

* __init__(): Initializes the player turtle with its initial position, color, shape, and heading.  

* go_up(): Moves the player turtle upwards by a fixed distance.  

* go_to_start(): Resets the player turtle to its starting position.  

* is_at_finish_line(): Checks if the player turtle has reached the finish line.  

<br>
<br>

**CarManager**  

Manages the creation, movement, and level-up of the cars in the game. It has the following methods:  

* __init__(): Initializes the car manager with an empty list of cars and the starting move distance.  

* create_car(): Creates a new car with a random chance and adds it to the list of cars.  

* move_cars(): Moves all the cars in the list of cars towards the left.  

* level_up(): Increases the move distance of the cars when the player successfully crosses the road.  
 
<br> 
<br>  
  
**Scoreboard**  

Displays the current level and game over messages on the screen. It has the following methods:  

* __init__(): Initializes the scoreboard with the starting level and sets up the turtle for displaying the score.  

* update_scoreboard(): Clears the current score display and writes the updated level on the screen.  

* increase_level(): Increases the current level by 1 and updates the scoreboard.  

* game_over(): Displays the game over message on the screen when the player collides with a car.  


# Interface 

<br>

![Turtle Crossing Game](https://github.com/filosoho/Turtle-Crossing-Game/blob/318466586fc12eb5b6571a307d3a7b6daee3581c/1.png) 

![Turtle Crossing Game](https://github.com/filosoho/Turtle-Crossing-Game/blob/318466586fc12eb5b6571a307d3a7b6daee3581c/2.png) 


<br>

# Contributing
If you would like to contribute to this program, feel free to submit a pull request. Please include a detailed description of the changes made and the reasons for the changes.

# License
Feel free to use and modify the code as per your requirements.  
