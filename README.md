# Accelerometer-Lightsaber-Game
Objective: When the accelerometer reading turns to the lowest point serial monitor the lightsaber should turn off and gets deactivated game stops you lose: 
In order to win: Your movements should be constant without the accelerometer readings turning off: The intensity of the lights should get higher. The goal is to beat all three levels for 10 seconds without shutting the led lights off. When the next level is reached the lights should be more sensitive to accelerometer readings and your strikes should be more precise. Blue lights are the 1st stage, green lights are the second stage, and red lights are the 3rd stage. 

Levels: Set a timer. There are three stages, the first stage is the longest one, the last stage is shorter and movements are quicker. The lights will change indicating a change in level. Since movements depend on the amount of g’s the accelerometer reads higher gs will read stronger movements. The settings can be changed to play in easy mode or harder mode by changing the number of g’s the accelerometer reads in the serial monitor. 

Goal: keep your lightsaber moving 

Inputs: 

Defensive movement:
Z movement: upward and lower strikes

Offensive movement:

X movement: strike towards opponent
-X movement: strike away from opponent

Y movement: strike from the Right side 
-Y movement: strike from the left side

Output:

Sound sensor for the opponent. 
Play a sound when the lights turn off. 

Functions:

The range of values for the led brightness are given by the map functions:
The maximum led brightness is 25;
The minimum led brightness is 15; 
There are three timers,
An async delay function that lasts for 15 seconds, then 12 seconds, then 10 seconds
