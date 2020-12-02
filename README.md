# Snake-game-implementation

                                  METHODOLOGY

We will create different function for each functionality in the game such as for creating
boundary/wall, snake movement and many more.

Step 1: Learning Some Basic Syntax for Devolping Gui You can add colour and you can print where you want to write You
need to learn basic syntax like:
1)gotoxy(x,y)

2)textcolour()

3)textbackground()

4)kbhit()

Step 2: Welcome Page of the GameUsing above select proper background and font. Welcome the user by showing game title.

Step 3: Selecting the Level and mode of Game.After displaying the game title. Show the levels and ask user to select the level and mode. Save the level selected by user in variable and use it to increase the difficulty level of user.

Step 4: Algorithm
Food creation : In this algorithm we will use predefined function to create a random number inside the boundary. Each time a function is called it generates a random number.

Random function : In c program there is a random function(rand()) which is used to place the food at any point on the screen.Thus,use this function to place food at any point on the screen.

Changing Direction : The direction of snake can be changed using kbhit() function. When you press the character accordingly it will change the direction of the snake.

Step 5: Algorithm for Increasing Size of Snake and Increasing Score Increasing size of snake: 

When snake moves forward it's size increases and when the coordinate of snake match with food coordinate then the size of snake is increased.
Increasing score: When snake eats the food the score of the user is also increased

Step 6: Game Over Condition:
When snake touch the boundary of the screen. The game over will come. This can be done by comparing the coordinate of boundary with the snake co-ordinate.

Step 7: Quit Page
Last step ask user if he wants to continue playing or not.

                                     All About Code
                                     
1. PRINTING THE SNAKE BODY AND BOUNDARY OF THE BOX : We have defined 2 function for printing the snake body and boundary for 2 different modes

2. Generating Food : We will only add one food in the whole box. We will keep track of the food with a variable also named food.Then we will generate food randomly inside the                        box avoiding the snake parts.

3. DIFFERENT MODES & DIFFERENT FUNCTIONS : In single player mode and multiplayer mode we have 3 different mode respectively i.e
    1) Easy 
    
    2) Moderate
    
    3) Hard
    
    And for all these mode we have defined different function as follows
   
    1) For Single Player mode
    
       a) void snake_movementeasy()
       
       b) void snake_movemenmoderate()
       
       c) void snake_movementhard()

    2) For Multi Player mode
    
       a) Void snakemulti_movementeasy()
       
       b) Void snakemulti_movementmoderate()
       
       c) Void snakemulti_movementhard()

4. Snake Tail Movement and Size:

    a) In this we have created a snaketail_movement for single player mode and snaketailmulti_movement for multi player mode.
    
    b) These function are looking after the movement of snake as well as helping in increasing the
       size of snake.

5. Game Over: In this we have defined the game over condition and activites that are to be performed after the snake dies.

6. More Functions : We have some more functions like 

    1) Loading Screen – It has code which shows our first screen of the game with slowly loading screen.
    
    2) Starting Screen – It has code which displays our main menu screen.


