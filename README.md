This is the rocket simulation which is associated with my college application.
To navigate around the system use this tutorial:
HOW TO ACCESS UPON LAUNCHING THE PROJECT FILE: OPEN CONTENT DRAWER -> CONTENT -> SAVE 1 THE SIMULATION IS MADE TO WORK DIRECTLY IN SAVE 1. TO START THE SIMULATION PRESS THE PLAY BUTTON. Logically, you must download unreal engine to run the project.
Q/E to change Yaw
A/D to change pitch
Z/C to change roll
W/S to change throttle
X to toggle 
SPACE BAR to launch
Arrow keys used to change camera. Warning: It can make the perspective weird.
Known Bugs:
>This one is quite rare yet most annoying: The rocket may start uncontrollably rotating prior to launch. If that happens, delete the previous model and spawn in a new one. Set its location in the details panel to (0, 0, 637110.0). Notice that the rocket must be slightly above the ground to avoid collission.
>Calculations may not work correctly upon toggling the prediction line if the computer used to access the link is not powerful enough. I had the issue happen to me personally on a laptop, leading towards me making the prediction line weaker utilize less time steps.
>Memory overload pop-up: It should not be a large issue when it shows up. It just means that the memory on your computer is running out yet the project still runs correctly.
Things to know:
>The main rocket is saved as BP_RocketSimulation. to view my work open the blueprint and look at functions. The main functions are called in the event graph, and some of them call functions inside of themselves, which are smaller calculators.
>If you want to see the rocket's properties, do it through the blueprint in the viewmodel tab.
>Niagara system and blender model is saved under Rocket folder.
>Refer to IMC_Rocket if encountering any errors in controls. If you have to change bindings, it can be done safely.
>Rocket_Backup is a simple backup and should not be spawned in. However you can look back to it and see how some progress evolved. I updated the backup save as I went.
