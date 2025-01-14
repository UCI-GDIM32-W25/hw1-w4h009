[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity

Put your notes from the W1L2 (Thurs, Jan 9) in-class activity here.
https://docs.google.com/document/d/1Ya_9R7ukZXo761YQaIgZNAo7-dg3Yae3iqlFys7UMxY/edit?usp=sharing

HW 1 Activity
Objects
    Player
    Plants
UI
    Seeds Planted
    Seeds Remaining
Player Attributes and Actions 
    Moveable
    Can plant
    Seeds remaining
Plant attributes and actions
    Plantable
    Hidden until planted
Interaction
    Player can place plants when pressing space
    When player runs out of seeds, can’t plant anymore

## Devlog
Prompt: Include the HW1 break-down exercise you wrote during the Week 1 - Lecture 2 (Jan 9) in-class activity (above). If you did not attend and perform this activity, review the lecture slides and write your own plan for how you believe HW1 should be built. If your initially proposed plan turned out significantly different than the activity answers given by Prof Reid, you may want to note what was different. Then, write about how the plan you wrote in the break-down connects to the code you wrote. Cite specific class names and method names in the code and GameObjects in your Unity Scene.


For the most part my project turned out the same as I planned in in class. There are two main objects, the player and plant prefabs. The UI consisted of the seeds planted and the seeds remaining for the player. The player is able to move and plant seeds and plants will appear when the player does so and will not appear until planted. The player can place plants when they press space, and when out of seeds, the player can no longer plant. In order to move the player, I added a script component and used translate on it's transform component in order to move it when a direction was inputted. I gave it the ability to plant by adding a plant script which excecuted when the spacebar is pressed. When pressed, it calls the plantseed method if there are seeds left. The plant seed method updates the plant UI and instantiates a plant. In order to update the plant UI, I call the UpdateSeeds method in the plantUI script which updated the UI with the given values.


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
