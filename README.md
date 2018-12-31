Author: Chayuso - Christopher Ayuso
Course: Fall2018 - CS171

----------------------------------------------
Introduction
----------------------------------------------
In Wumpus World, the AI agent must attempt to return to its origin with gold while 
avoiding pitfalls and the Wumpus. The agent only perceives the current tile that 
it is on. Standing on a breeze means that there is at least one pitfall adjacent to 
that tile and stench for the single Wumpus. One arrow can be fired from the agent's 
direction to kill the Wumpus, but must determine whether it is a logical decision to 
do so.

----------------------------------------------
Setup
----------------------------------------------

Run the Main.py file located in the 'src' folder in order to test MyAI.py.

Running the world_generator.py file will construct a full tournament set of 10,000
worlds used to test the AI agent. This script can also be ran from Main.py if no
set is detected in the "Worlds" directory. If you do not wish to generate a tournament
set, a random world will be generated instead to test.

Each tournament set contains a set of:

2500 4x4 worlds
500  5x4 worlds
500  6x4 worlds
500  7x4 worlds
500  4x5 worlds
500  5x5 worlds
500  6x5 worlds
500  7x5 worlds
500  4x6 worlds
500  5x6 worlds
500  6x6 worlds
500  7x6 worlds
500  4x7 worlds
500  5x7 worlds
500  6x7 worlds
500  7x7 worlds
