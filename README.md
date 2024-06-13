In this project, you have to make an animation of infinite length and phase I includes printing of “still” main screen only (without any movement).
[Phase I – Printing Main Screen] Your main screen should fulfill following requirements:
Your main screen will be divided into three parts: background, foreground and reserved space.
Background: Top 1/3rd (or so) of your screen will have some background with objects e.g. mountains, buildings, trees etc.
Foreground: Middle 1/3rd (or so) of the screen will have some foreground with objects e.g. road having some vehicle(s) or sea having ship(s) etc.
Reserved Space: Bottom 1/3rd (or so) will be reserved “still” space may be part of sea or grass.
Currently the scene will be either daytime or nighttime; no change is required in main screen in this phase.
[Phase II - Animation]
You have to move
1st partition rightward and
2nd partition leftward
Important Instructions: Now your main only has two function calls, i. PrintStartScreen ii. PlayAnimation in infinite loop where PlayAnimation is just a movement by one unit (doesn’t contain any loop) and the infinite loop in the main is giving the effect of animation.

[Phase III – Keyboard Interrupt]
You have to implement “Jumping Rabbit” from “Piano Kids” (you can download this application from app store) in the 3rd Partition and display the score on top right of your screen. We are working with ‘Up’ key instead of Tap functionality. Functionalities which are required in phase III are as follows:
We are not handling blue bricks in this phase, breaking blue bricks functionality will be added in timer phase.
We are only adding yellow and orange bricks in phase 3. Change the color with alternate bricks; make it random in next phase (timer).
Start the initial position of new brick at some constant location in this phase. After timer new brick’s location (column number) will be random.
We are not adding Bees in this project.
For now, carrots will be appearing at constant location with alternate bricks, in timer phase this will be randomized.
If rabbit collects the carrot, score will be updated.
According to the game, change the frequency of brick movement with score.
If rabbit jumps in the air, the game will be over and it should successfully terminate.

[Phase IV – Timer Interrupt]
Following are the functionalities required in this phase:
Breaking Blue bricks using timer.
We are supporting all the colors of bricks and their functionality according to the game. Color of new brick will be random.
Location (column number) of the new brick will be random.
Randomly carrots will (or will not) appear with new bricks.

