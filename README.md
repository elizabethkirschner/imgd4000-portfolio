#Development Portfolio

  I worked on the checkpoint and respawn system, the enemy system and the collectible and level change system in our project. These tasks required creating custom game modes and game states as well as editing each level blueprint to accommodate the use of simple cinimatics for the player deaths and level changes. 

2. Some of the biggest challenges were incorporating the use of cinimatics as transitions.  I could find no c++ code examples to help me understand how to implement them. I did find simple blueprint examples, and was able to rework the collectible and enemy systems to incorrporate the use of blueprints. I also had trouble with the level system, as game state is not preserved across levels, this made it difficult to set up a more abstract level change system. In the end, I made the level change system hard coded in each level blueprint.

3.

4.

5. (links to the tutorials)

  We chose Perforce as our version control system. None of the team members had prior experience with Perforce before this project. We did not have a great experience with Perforce. I found it difficult to use and not intuitive to learn with previous experience with git. The largest difficulties we had with Perforce came from the file locking system. At least within our understanding, once a file is locked,
there is no way to unlock it without either submitting a changelist or reverting the file. If there are local changes this can be difficult. We also experienced that the  file locking system will not prevent a user from submitting changes to that file, but the file will not be changed. This caused some serious distruption at one point during our project where I myself pushed changes that ended up not compiling for all other members of our team. The biggest problem with this was that perforce gave me no warning that this file would be overwritten. From my end, everything seemed fine. I also personally had a hard time adjusting to the P4v interface. I know there is command line tool, but since the rest of my team was using the editor I felt it maded more senes to work in the same environment as them. I know not everyone prefers the command line, but in my personal experience with git the command line is far easier to work with and understand.
