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

----------------------------------------------
Course Tournament
----------------------------------------------
The tournament_Bonus.xlsx file contains the records of AI scores for the official course tournament. 
Each team is either comprised of 1 or 2 team members. This AI, "Chayuso", was able to reach the 
top 10% tier but still has room for improvement. The FinalReport.pdf gives further details on how the 
AI agent was written.

----------------------------------------------
Video Demo
----------------------------------------------
[![Wumpus World AI Example](https://img.youtube.com/vi/ml3kfS_eUT4/maxresdefault.jpg)](https://www.youtube.com/watch?v=ml3kfS_eUT4 "Wumpus World AI Example")
