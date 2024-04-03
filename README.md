[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [Eddy Yat Long Chan]
### Student number: [47425083] 

![](DocImages<1.png>)

This is the original sketch/plan of the game I want to design. It is a 3 section level. The idea is that the player starts in box number 1 and as the player progresses through, they should get familiar with the movement mechanic of the game. There are various traps and monsters placed around the level/room for the player to recognise its dangers. Like at the start where there is a spike trap and a health pack next to it, it will allow the player to learn what it is.

![](DocImages/<2.png>)

The trap is placed to remind players to be aware, after passing through the spike there is a moving platform where it introduces another mechanic where it requires the player to crouch and let the platform move, after that stage they should be able to see that the only path forward is upwards and the player will be rewarded 1/3 keys for their efforts, eventually there will be checkpoints to let the player know that they are going in the right direction. I had to scratch the door idea because I want to expand the map and make it look like it has more content and less restrictions. 

![](DocImages/<creeper.png>)

The second floor consists of obstacles and objects to tests the player’s understanding of the movements practiced in room 1 and the reward for completing the course is 2/3  keys, There will also be weapons placed at the start and end of room 2 for players to prepare for the increase of difficulty, The staff will be the weapon the player gets first and the gun is the second one, it is placed in such an order to teach and control what the player does. The mechanic the player learns in this level is using weapons while doing movement, the weapon can also be used to hit through objects. As for health, heal packs will be intentionally placed more frequently to ensure progression of the players.


This level is designed to be slightly more difficult because the spitter was intentionally placed in a place where the player cannot jump to, but combining jump with staff attack will get the job done just fine. The moving platform doesn’t go all the way to the end but it’s just enough for the player to curve around and reach the top. Once at the top the player is given a checkpoint and a chance to whack the monsters inside the acid through the walls (can be done to the other monster in the acid on the right as well), these jumps are all possible although it seems hard.

The method of flow is the key placements, after getting the first key it encourages the player to go forward and knowing the second key is within reach it will encourage the player to go forward no matter the difficulties as the health packs given are generous.

![](DocImages/<3.png>)

Finally, Room 3/level 3 the hardest room and the final room to the exit, in order to maintain a possible way to finish the game there are less but well placed health packs, This room mostly consists of obstacle courses and not much fighting. However the movements learned from previous rooms are combined and used in this room. The height of the room is intentionally longer, that way the player won’t have a clear visual on what the next obstacle would be. There are platforms placed to help them see clearer but crouching for a period of time will move the camera down as well. The part to advance is a moving platform that goes at a moderate speed and it’s dangerous and seemingly impossible but it is actually very easy. The cut off part of the map from the player’s perspective will hopefully encourage the player to explore. The final key is revealed at the very end, There is only 1 path so it’s impossible to get lost. There are bugs throughout the playthrough and I turned it into a feature of the game, bugs such as getting stuck in blocks because of the moving platforms. I put acid inside the blocks in case of such events the player will be reset to the checkpoint. 


//Storyboard//
 
![](DocImages/<5.png>)

At the start, the player starts in the very left corner of room 1 and there are hearts which represents a player’s health as shown by the blue arrows on the top left, there are also 3 empty key slots on the top right of the screen as shown by the blue arrow on the right.  

![](DocImages/<4.png>)

To advance in the game the player needs to use the jump key and make their way around the obstacles to reach the next area to proceed. 

![](DocImages/<6.png>)

These are health packs and they are placed all around the map for the player to Interact and take to heal up the health they’ve lost.

![](DocImages/<7.png>)

These are spike traps and they are placed all around the map, when touched the player loses 1 health point and becomes invincible for 1 second. 

![](DocImages/<8.png>)

The circled in red is a moving platform, it helps players get to places efficiently and effortlessly, can be combined with crouch.

![](DocImages/<9.png>)

This is “acid” it takes away 1 health point from the player and resets the player back to the last checkpoint. 

![](DocImages/<10.png>)

The item circled in red is a key, this is 1/3 keys needed to open the exit door to escape this dungeon. The player will need 3/3 keys to complete the dungeon.

![](DocImages/<11.png>)

This is a checkpoint activator, when near it will automatically activate the checkpoint so in the event of the player dying, they will respawn here.

![](DocImages/<13.png>)

This is something the player can loot f, there could be various weapons gained by walking up and collecting them.

![](DocImages/<14.png>)

This monster is a “spitter”, they can attack the player at long range. It deals 1 health point and deals knockback, it grants the player 1 second of invincibility. 

![](DocImages/<15.png>)

Attacking can be used to attack enemies, it launches the player slightly forward and it takes out the enemy instantly.

![](DocImages/<16.png>)

This monster is a “chomper” . It does close range melee damage, it deals 1 health point and deals knockback, it grants the player 1 second of invincibility. 

![](DocImages/<17.png>)

The platform the player is standing on in the image is a pass through platform, simply pressing s and jumping will allow the player to phase through.

![](DocImages/<18.png>)

This is the exit door, after collecting 3 keys that means that the player has completed all the trials of the dungeon and therefore granted to leave player can gain access to the final door and leave the dungeon safely.


//Molecule Diagram//

DocImages/molecule-diagram.png

Reflection


Iterative design improves my level design because it is a pattern that players can get comfortable and get use to, it contributes to the advancement of the game as the player can try over and over to hone their skills without the need to worry about needing or finding another way to deal with situations presented in front of them.  After repeatedly fixing and improving the game, everything started to piece together and a lot more creations were implemented. When the game was first created there were a lot of errors, like when the rooms don’t look right or when the moving platforms can lead to a player being stuck and therefore cannot progress, I have to find ways to counter or change the design completely to fit what i'm looking for. 

I had an idea of having each level be unlocked by a door with a different key, but later on the map looked too small so I decided to change it into something bigger and require much more to achieve, it was through iterative design I was able to create the map I have now. There was also a part I made way too difficult so after some refining it was back to moderate just how it was supposed to be. At the beginning I put the trap way too close to the ceiling and it made the trap unavoidable so I had to change the map layout for it to work. There was acid placement where I was stacking a whole bunch and it didn’t look as clean as I thought so after a few more tries I managed to change the size through an inspector in unity. In the third level the original acid pool at the bottom wasn’t that small but after realizing I can't get through the level without minimizing the size, I changed the layout and made it work. 

In conclusion, Iterative design helps improve designs because through trial, mistakes will be noticed and taken care of and different ideas over time will come up for use, during the making of the game there was lots of problems solved and modified and without iterative designing the game won’t be playable because the character would just get stuck. Play testing is also important as it can provide a better visual of problems that may occur and it could be noted down and looked after. 



