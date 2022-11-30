# HW2_McKayS
Sam McKay

Notes: I've reached out to Mr. Ortega regarding an imbalance between my partner and my work and so he allowed me to be graded alone for this project.

To Start Game: Since I will be showing my demo within the Unreal Editor all I have to do is ensure that the Quest 2 is connected to the computer, the oculus app is open then I will be able to select "VR Preview".
From here A main menu will appear with full vr capabilities. The main menu will contain a "Play" and "Quit" button that the user can select by moving the motion controller and then pressing the trigger. If the player selects "Play"
they will be transported to the first level of the game where they can see a table with three guns and a bomb. Above this table is a red timer counting down from 3 minutes which the player must survive the on slaught of enemies.

Keybindings: The bottom trigger on both the left and right motion controllers allow the player to pickup weapons, this button must be held down to continue holding a selected weapon. Once a weapon is held the player can press the top 
trigger on either controller to fire that respective weapon. The right joystick is used to teleport around the top of a tower as well as floating platforms that surround the top of the tower. The left joystick is used to turn in 30 
degree increments. I also implemented an upgrade/information system that can be accessed by pressing the menu button on the left controller. Here the player can see the tower's health, how much gold the player has, or buy new weapons to 
enable dual weilding/return weapons that may have fallen off of the top of the tower. 

Pickups: There are four pickups in the game: 
* Explosives that deal radial damage to enemies after a three seconds once the player has released the bomb
* a pistol that shoots large, slow bullets
* a rifle that shoots smaller, faster bullets
* and an smg that shoots small, fast bullets when the tigger is pressed and when it is released, this creates the effect of a rapid fire weapon.

Attempt to reduce motion sickness: I found that the best method of travel to reduce motion sickness was a teleport system since it doesn't give the player the illusion of movement, a turning mechanic to reduce the amount that a player 
has to physically turn, and a plane that the player travels since movement in the Z axis can often give the player the sensation that they are falling even when they are not.

Assets: There are several assets that have been implemented so far: A bomb static mesh that was used within HW1, the standard pistol mesh that is starter content for unreal development, a modification of the pistol mesh to make it appear 
longer, another modification of the pistol asset to make the pistol appear thicker and little bit longer, an enemy that looks like an eyeball with horns and a crown that I designed in Blender, a mechanized bug that I also designed in Blender,
a wizard that I imported from the unreal market place, tree assets that were imported from the unreal market place, and the tower that I created in the unreal editor itself.
