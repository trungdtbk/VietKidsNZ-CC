# **Tank - 2 Player**

Build a two player tank game on Scratch. The red tank and blue tank move around a maze looking for each other and shoot at each other. Something like this:

![](/images/tank/1.png){: style="max-height:400px;width:auto;height:auto;"}

 
!!! info "You will need several techniques to do this. Let break it down"

    1. You need a Maze and program it so that the tanks cannot run over it

    1. You need to program the tanks so that it moves left, right, up, down when a key is pressed

    1. You need to program the bullet so that when a key is pressed, it flies

    1. You need to program the tank so that when it got hit by a bullet it dies

??? "See how it's done here"

    #### Make a Maze

    You can make a maze by simply drawing a filled rectangle and erase some parts of it.

    Create a Sprite and name it **Maze**. Then, go to the Costumes and create a new Paint costume.

    Draw a rectangle, fill it with your favourit color. Then, use the eraser, set the size and erase the rectangle to make a maze:

    ![](/images/tank/2.png){: style="max-width:300px;width:auto;height:auto;"}

    Now, go to Code and add this:

    ![](/images/tank/3.png){: style="max-width:300px;width:auto;height:auto;"}

    !!! info
        The **go to ... layer** makes the Maze go under the tank, otherwise you won't see them

    ### Make the first tank player

    Create a new Sprite and named it **Red tank**. Now, you need a tank costume for your tank. You can draw yourself one or Google it. This ![](/images/tank/red_tank.png){: style="max-height:20px;width:auto;height:auto;"} can be the one.

    Now, you will need several variables to keep track of the tank's direction and its position (x, and y). Let make some variables and call them: **red direction**, **red x** and **red y**.

    The player needs to be able to control the tank, like pressing the **up arrow** makes it go up, **down arrow** to go down and so on. This code will make that:

    ![](/images/tank/4.png){: style="max-width:300px;width:auto;height:auto;"}

    Now, test to see if it works

    ???+ "How this works?"
        The first **if..then** says if the **up arrow** is pressend, then change the tank direction to 0 (mean :arrow_up:). 
        180 for :arrow_down:, 90 for :arrow_right: and -90 for :arrow_left:

        The **move** makes the tank move 3 steps (pixels) for every press.

    It looks ok now. But the tank can run over the maze. That's not right. Can you fix that? How do we know if the tank runs over the maze?

    !!! info "More to come later..."