[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity
HW 1 Activity

- Objects
    - Player
    - Plants
- UI
    - Seeds Planted
    - Seeds Remaining
- Player Attributes and Actions 
    - Moveable
    - Can plant
    - Seeds remaining
- Plant attributes and actions
    - Plantable
    - Hidden until planted
- Interaction
    - Player can place plants when pressing space
    - When player runs out of seeds, can’t plant anymore

## Devlog
For the most part my project turned out the same as I planned in in class. There are two main objects, the player and plant prefabs. The UI consisted of the seeds planted and the seeds remaining for the player. The player is able to move and plant seeds and plants will appear when the player does so and will not appear until planted. The player can place plants when they press space, and when out of seeds, the player can no longer plant. In order to move the player, I added a script component and used translate on it's transform component in order to move it when a direction was inputted. I gave it the ability to plant by adding a plant script which excecuted when the spacebar is pressed. When pressed, it calls the plantseed method if there are seeds left. The plant seed method updates the plant UI and instantiates a plant. In order to update the plant UI, I call the UpdateSeeds method in the plantUI script which updated the UI with the given values.

## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites

## Prof comments
Your Devlog satisfactorily answered the prompt, so you'll get full marks, but I would have liked to read a few more details about the implementation of the methods that you named. Still, I'm glad you connected the break-down to the different Components and methods you used.

Please consider formatting your break-down activities with the hyphen '-' symbol as suggested above. Also, you can remove the prompt text. This will make it a lot easier for me to read. See the [README formatting guide here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
