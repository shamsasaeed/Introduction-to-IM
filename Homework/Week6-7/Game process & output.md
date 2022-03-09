##  Ghost Buster

# Summary concept of the Game:

The idea of 'Ghost Buster' that I have created is a spooky game that involves a screen that a player had to click on. After clicking on the introductionary screen
there would be colorful bright ghosts flying around. The player's goal is to click as many ghosts as she or he can. To make the game more interesting I added a 
time limit, and within each click, a player gets a point. However, if a player clicks on the background instead of the ghosts then a player's points gets 
deducted. The player wins by earning as much points as possible before the time ends, if the time ends then the player has to play again to try and get higher 
points from the previous game. This was made intentionally because I wanted this game to be addictive and competitive to the play so they would play again and 
again! To make the game more complicated, I made the ghosts move in a desired speed to make it harder for a player to get a point when trying to click at a ghost.
Before the game starts, it displays and spooky door, and asks for the player to 'double click' to start. When the player double clicks it takes them to another 
spooky house bachground where the game begins. When the time ends, the player has to double click again to restart the game and try to get higher points.

# A challenging concept I couldn't cover:

Something I wanted to add but didn't have time to do was that I wanted each color of the ghosts from the yellow, the green, and the pink to each have different 
number of points. For example, I would have made the pink to have five points instead of one and the green to have two points instead as well. I would have made
the ghosts with more points to appear less than the ghosts that have less points to make the game more intense. Howeevr, Even though I didn't have time to do 
that, I am still very proud of the output I have achieved from all the hours of hard work and improvements that were made and got adjusted so I can finally be 
happy and proud of the result and final output. I am very content with my game now, but maybe I would consider taking that challenge of what I couldn'r cover,
and try this out very soon to see if I can get this challenge defeated which I am pretty sure I can and will!

# Some important contributers I used in my code:

- Arrays
- Classes
- Functions
- Else-if Statements

# Coding proccess:

In the beginning of my coding process, downloaded the background, sound, and text. I started with defining the two backrgound names that I used, the 
green/pink/yellow ghosts, and also craeted arrays for the ghosts. Then when developing my game I noticed that I needed to add a timer and points, so I 
set the timer to 30 seconds and  points to 0. In the beginning this step seemed easy, but it definitily got more complicated. After that, I added the 
function preload which I needed for the two background images,the sound, and the font. For the background, sound, and font I was looking for something 
that would match the theme of my game, and even though it took a while to find what suited my game, I loved what I chose. After that I started writing 
the function setup for the green/pink/yellow ghosts using x and y values. This was a long process but it wasn't hard repeating the codes since they were 
all similar, the only thing that's different is the colors of the ghosts, which I insisted of doing. Then the longest coding is the drawing function 
which has basically everything the code is meant to display for the game like the background, the text, etc. 

Then I created seperate classes for each ghost color where I added the contructor, the the draw, the move, and finally, the reset to use later on. 
Even though I had to create three classes they also were the same, except the color of the ghosts. I also had to add the js files into the html for 
the classes to be seperated into different files. Then I wrote the code of function mouse double clicked which would allow the player to move from 
the start page to the actual game and this involves the change of screen. I also wanted the sound to appear when the actual game started. Now came 
the tricky part, which started when I used mouse is pressed and if statements. I created three if statements for each colored ghost so that the points 
would increased when they are clicked,and the fourth if statement involved the decrease of points when the screen is clicked instead of the ghosts. 
Finally, I used the reset function to  reset the game including the points back to 0, the timer back to 30 seconds, and the screen back to 0. The long 
procces made the game very intersting!

# Hardships during coding process:




























# Conclusion:

In conclusion, I really enjoyed this experience. I never thought I would create a game, especially in coding, and seeing my ideas come to life makes it 10X 
better. Also mentioning that even though I came accross many hardships and errors, I had fun with playing around to fix my mistakes and trying out something 
new. And if my fixing didn't work out I'd try another solution then another one until the code turn out perfect and I get the final output I was waiting for.


# Final result Code:


# Final result output:

![final show 1](https://github.com/shamsasaeed/ssa8778/blob/main/stars.png)

![final show 2](https://github.com/shamsasaeed/ssa8778/blob/main/stars.png)




# Link to game:

[click me to play Ghost Buster!](https://editor.p5js.org/shamsasaeed/sketches/K_1UqYEQS)


