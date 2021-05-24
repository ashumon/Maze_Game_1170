# Maze_Game_1170
Simple maze game made with Python Turtle library for a group project
# 1.) Define the playing screen
# 2.) Create an iterable list that will become the walls of the maze
#     We will use the built in turtle.stamp() feature, which
#     places an unmoving "stamp" of the turtle. Can use different colors or shapes.
# 3.) Create a nested loop to iterate through the list "maze" and actually stamp the screen
#     The positions are x, y coordinates, which is why we need the nested loop
# 4.) Create the player
#       - This involves getting input from the user for the SHAPE of the turtle
#       -This also involves getting input from the user for the OUTLINE color of the turtle.
# 5.) Create a way to move the player on the screen. We can move in four directions - up, down, right, left
#       This function needs 'sub functions' to define those directions and what to do (how far to move, using coordinate system)
#       we also needed to use the turtle.listen() command to allow for input from a keyboard
#       the turtle.onkey(function, 'keyboard item you want to use') utilizes those sub functions defining the directions and what do do
# 6.) Output a message of encouragement to the player at the bottom of the maze
