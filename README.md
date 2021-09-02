# Exercise-01d-Score-and-Moves
Exercise for MSCH-C220, 2 September 2021

A demonstration of this exercise is available at [https://youtu.be/aHoioTsRz9U](https://youtu.be/aHoioTsRz9U)

This exercise should give you the last piece that you need to successfully implement the basic solution to Project 01. We will be adding a score and moves counter to our interactive fiction game.

Begin by Forking this repository. Check that it has been forked successfully; the repository should now read [your username]/Exercise-01d-Score-and-Moves

Edit the LICENSE and replace BL-MSCH-C220-F21 with your full name. Commit your changes.

Press the green "Code" button and select "Open in GitHub Desktop". Allow the browser to open (or install) GitHub Desktop. Once GitHub Desktop has loaded, you should see a window labeled "Clone a Repository" asking you for a Local Path on your computer where the project should be copied. Choose a location. Make sure the Local Path ends with "Exercise-01d-Score-and-Moves" and then press the "Clone" button. GitHub Desktop will now download a copy of the repository to the location you indicated.

Open the folder in VS Code. You should see four files: .gitignore, LICENSE, main.py, and README.md. Open main.py.

In main.py, you will see a mostly complete interactive fiction game engine, with the render, update, and get_input functions implemented. The Zork Twine story we have been working with has been exported as JSON and included as a dictionary (lines 5–220). Your task is to keep track of the player's moves and reward the player with a score if they visit certain locations.

As part of the render function, you should add a print statement that displays the following:
```
Moves: 0, Score: 0
```

The moves and score should then increase as the player moves around the world (you can increase moves by one ever time through the game loop). moves and score are integers, so to concatenate them with a string, you will need to use the [str() function](https://www.w3schools.com/python/ref_func_str.asp).

Next, you will need to edit the world dictionary to add a "score" key to the Kitchen and the Tree. The player should be awarded 20 points for visiting the kitchen and 10 points for visiting the tree. As an extra point on the Project, you can figure out how to only award these points once, but for this exercise, you can increase the score every time those locations are visited.

As always, you can implement this however you would like to, but if this seems overwhelming, feel free to follow my video demonstration. When you are  done, run the program to make sure it is functioning correctly. Then, save your files and return to Github Desktop.

In GitHub Desktop, you should now see main.py highlighted. Add a Summary message at the bottom of that panel, and push the "Commit to master" button. On the right side of the top, black panel, you should see a button labeled "Push origin". Press that now.

In GitHub Desktop, you should now see main.py highlighted. Add a Summary message at the bottom of that panel (something like "Implements game loop"), and push the "Commit to master" button. On the right side of the top, black panel, you should see a button labeled "Push origin". Press that now.

If you return to and refresh your GitHub repository page, you should now see that your files have been changed (with a new date).

Now edit the README.md file. When you have finished editing, commit your changes, and then turn in the URL of the main repository page (https://github.com/[username]/Exercise-01d-Score-and-Moves) on Canvas.

The final state of the file should be as follows (replacing my information with yours):
```
# Exercise-01d-Score-and-Moves
Exercise for MSCH-C220, 2 September 2021

A simple interactive fiction game engine, that allows a player to navigate through eight locations from classic Zork, implemented in Python. Moves and a score are also tracked and reported.

## Implementation
Created using Python 3.9

## References
[Zork, 1977 by Tim Anderson, Marc Blank, Dave Lebling, and Bruce Daniels](https://en.wikipedia.org/wiki/Zork)

## Future Development
None

## Created by
Jason Francis
```
