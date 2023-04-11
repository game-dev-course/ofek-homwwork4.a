# ofek-homwwork4.a


my game for homeowrk4 part A


i did allmost all the optionts(i only didn't do the 3 lifes) my improvement was the speed boost powerup


1. for the shield what i changed was fineding the circle object that is part of the player and via the dhield code
make it visibale and than decrese the alpha value, after 5 seconds make it not visable again


2. for the difrent shoot i used the code of the shield but insted of changing the circle i got the script object of the shooting action and changed
the prefab it uses, also changed the colision code so i can enable the disable what get destroyed(here the shot does not dissapear after hiting a target)


3. delay for shooting, i changed the spawnclick code to save the time of the last click and then evrey time you click it checks if x time passed from the last time you clicked and shoot


4. the two enemy types, i didnt changed a code of the score gaining to let you choose the enemy type and score value, i make it faster by changing the speed in the prifab's script of mover, then let the spawner to spawn this enemy too

5. i created a new script that let you choose the wall objeccts(roght left up down) as borders and if you you hit one of the walls it takes the screen hright or width and substarct or add it to the player location


the git with all the files is at


[GitHub](https://github.com/oa1321/ofek_homework4_part_a)


[itch](https://gamedevcourse.itch.io/ofek-homework4a)


unity 2021.3.21f1 LTS
