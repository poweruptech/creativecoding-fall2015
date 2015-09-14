## Learning Objectives:

1. Learn definitions of coding, algorithm
2. Learn about how many types of computers there are and how many places code exists
3. Learn two examples of simple algorithms (draw a square, rotate a shape to make a spirograph)
4. Introduce Scratch and IDE, set up user accounts
5. Outputs: Draw a square, use the square to create a spirograph
6. Introduce events * green flag clicked

## Lesson Plan:

1. Ice breaker / introductions
    * Name
    * Have you coded before?
    * What is your favorite thing to do on the computer?
2. Concept discussion
    * What is coding? Giving instructions to computers
    * What is made with code? Video games, apps, google search, powerpoint, web browser, google maps, ...
    * What is a computer? Any machine that can process data: laptop, Xbox, tablet, smartphone, fridge, car, microwave, robot, plane, ...
    * Computers are really dumb * they follow instructions (code) exactly. People are smart, they can add missing information.
    * We plan our instructions using algorithms. It’s like a recipe. A recipe is a plan to bake a cake or make lasagna. An algorithm is a plan to make a computer do what we want it to.
3. What are we going to do in this class?
    * Art and music using the computer
    * Art first:
        * We will make beautiful geometric patterns
        * We will make a cool optical illusion picture
        * We will create programs that let the player draw and apply special effects
        * We will learn how to edit graphics
    * Music second
        * We will make our own musical instrument
        * We will use loops to create a theme song like you might hear in a video game
        * We will record sound effects and edit them
    * We will teach you projects and give you ideas, but we also want you to feel free to make them your own * change them up, experiment, create cool new effects that we never thought of
4. Physical algorithm - square
    * This week we are going to start with geometric spirograph art
    * The first step is we need to draw a simple square * then we can do cool things with it
    * Have a kid stand up and walk around in a square on the floor
    * What were the steps?
        * Draw one side,
        * turn 90 degrees
        * Draw next side,
        * turn 90 degrees
        * Draw next side,
        * turn 90 degrees
        * Draw last side
    * This is called an algorithm - it is a recipe that lets you plan what to code. Just like you wouldn’t bake a cake without a recipe, you don’t want to start coding without an algorithm.
    * Remember this algorithm - we are going to need it in a few minutes
5. Let’s get on the computers
    * Browse as guest
    * Open Chrome browser
    * Navigate to scratch.mit.edu
    * Create an account
    * Write down your name, username and password
6. Open up the Scratch programming environment (use big screen to demo if available)
    * Point out the stage, the sprites, the blocks/categories and the scripting area
7. Change sprites
    * Delete the cat - right click and choose from menu, or scissors at the top of the screen
    * Click on the elf to see all the sprites in Scratch
    * Select the sprite that will be your player (to hold then pen) and click OK
8. Shrink the sprite
    * If the drawing sprite is too big, it will hide the beautiful design we are going to make
    * To shrink the sprite, go to the purple Looks category and choose “set size to 100%”.
    * Pull the block into the big grey area on the right side. This is where we write our scripts or code.
    * We need to change the number to change the size. We want it smaller, so we will pick a smaller number. Change the number to 25%. This will make it very small.
    * We need to tell the computer WHEN to run this script. All the when commands are in the brown Events category. Switch over there and find the “when green flag clicked” event.
        * All the events have a rounded top like a baseball cap. You need to remember to put a hat on all your code, or it won’t know when to run.
    * Drag the event into your scripting area and connect it above the purple block.
9. Test your code
    * Click on the blue full screen button at the top left corner
    * Once you are in full screen, click the green flag.
    * You should see your sprite shrink
    * Click the button in the top left corner to return to your coding window.
10. Code the sprite to draw a square
    * Look at the brown events * there is a hat called “when key pressed” - pull that one into your code
    * Choose a letter that will be your draw command
    * The next step is to put the pen down. This means that wherever the sprite moves, it will be drawing. The pen commands are in the dark green Pen category
    * Remember our square algorithm? Let’s turn it into code!
        * Move 100 steps command (need to adjust the number of steps because 10 is tool small)
        * Turn 90 degrees (change from 15 to 90)
        * Write all the commands out one by one
    * Run and test it to see the square * you will have to click the green flag, then press the key that runs the draw command
    * It will run too fast for your eyes * the square will appear but you won’t see the sprite move * you can add a wait (yellow Control category) to see it move. It will need to be after every side.
11. Add a clear screen command
    * Go to the events category and drag another “when key pressed” hat into your scripting area
    * Choose a letter that will be your clear command
    * Go to the pen category and find the clear block * put it under the new hat
    * Run and test * green flag, draw and clear
12. Let’s use the square over and over to make a pattern now
    * There is a repeat command in the yellow Control category. It is like an alligator that can open its mouth as wide as it needs to fit other blocks inside
    * Put the repeat block around all of the square block
    * Now we don’t want to just draw all the square on top of each other, so let’s add one more turn block at the end (inside the Repeat loop), but instead of change it to 90 to make a square, we will leave it at 15 degrees so that the square start to rotate
    * Run and test to see how it works * you will find the wait makes it very slow * reduce to 0.1 secs
    * Let’s to try get all the way around the circle. Instead of repeating 10 times, try 20 * then experiment to reach 24
13. The pen category has some fun commands including changing the color
    * Add the “change pen color by 10” command to the bottom, inside the repeat
    * Run again to see the effect
14. Open coding and experimentation time

Other questions that may come up

* Setting the starting position * if sprite is dragged to a new place on the screen, it will just draw there. You can initialize the starting position by using blue motion block “go to x:0 y:0"
* Making the cat stay upright * click on the “i” icon to open the sprite info and set the rotation style to side*to*side or fixed.