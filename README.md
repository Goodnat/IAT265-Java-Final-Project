# IAT265-Java-Final-Project
1. A brief introduction
My application is a baking simulator. Players follow the prompts in the application
and click or drag the mouse to advance the program.
2. Requirements implemented
Technical Requirements:
2. In the application ’s welcome interface, I used GeneralPath to draw a fivepointed star. In the kitchen interface, I used Recursion to draw a pattern as a
wallpaper. During the baking process, I used perlin noise to draw the smoke.
3. I draw a window in the kitchen interface and use the move method to move the
clouds and sun outside the window. During the baking process, the sky darkens,
and the sun becomes the moon. In the upper left corner of the kitchen I also
made a clock which can move according to the time of your computer
4. After baking the bread, the user will enter the workbench. I use the decorator
pattern to add three types of food: chocolate strawberry and banana. The user
can choose different food combinations to get different bread combinations.
Code Structure Requirements
4. For the factory pattern, the superclass involved in creating the factory, I use an
abstract class for the factory at the super level. I initialized Clock, Sugar, Yeast,
Powder, Milk, Oven, Fridge, BakingBowl, Fan, Bread, BakedBread, Strawberry,
Chocolate, Banana classes in the factory.
5. My BaseObject class is abstract class. It has abstract method draw. All the
subclass overriding this method.
6. It has no error in this application
ECO
I have sophisticated complex shapes that the pattern appears in the kitchen.
I have day/night shifting
I have cloud and sun moving animation, the intelligent fan that rotate automatic
when bread baking. I have clock rotate automatic.
When the user puts the baked material into the bowl, it will have the effect of
particle splash.
This application interactions involve with a human avatar.
All images except banana and banana piece and strawberry from internet are selfcreated with good quality.
References
Strawberry.png (used in StrawberryDecorator class)
https://www.pngfly.com/png-nohrn3/download.html
Banana.png (used in BananaDecorator class)
https://www.cleanpng.com/png-fruit-vector-light-yellow-banana-slices-bananadry-95511/download-png.html
bgm.mp3 (used in BakingPanel)
https://freesound.org/people/Mrthenoronha/sounds/476545/
fridgeOpen.mp3 and fridgeClose.mp3 (used in BakingPanel)
https://freesound.org/people/AshFox/sounds/174862/
milkdrop.mp3 (used in BakingPanel) 
https://freesound.org/people/14FPanska_Nemec_Petr/sounds/420227/
itemClick.mp3 (used in BakingPanel)
https://freesound.org/people/CmdRobot/sounds/264828/
openoven.mp3 (used in BakingPanel)
https://freesound.org/people/Jbricker1997/sounds/426392/
buttonClick.mp3 (used in BakingPanel)
https://freesound.org/people/dland/sounds/320181/
win.mp3 (used in BakingPanel)
https://freesound.org/people/elijahdanie/sounds/487436/
