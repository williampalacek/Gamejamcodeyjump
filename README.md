# Game jam Codeyjump
This repo contains our rendition of Codecademy's Codey jump.

 ### -An idea 
We wanted to create an infinite jumping game similar to Doodle jump with some slight visual and practical modifications along with a difference in core mechanics.

 ### -A problem 
A problem we encountered was that if the platforms were moved to the top upon interacting with the bottom border, they would retain their current properties, which would include its downwards speed, resulting in the downward moving platform moving faster than Codey naturally moving downwards. This meant that the platforms would outrun Codey.
 

 ### -A solution 
 A suitable solution to this problem would be to reset all properties along with velocities when the blocks interact with the bottom border. Furthermore, we could reengineer the block system, making it so that they are created and destroyed rather than moved.

 ### -An application(game) 
The group created a modified version of Codey jump, which is a project which is a part of the Codecademy Learn Phaser course. This project is in and of itself a variant of the popular game doodle jump. This game uses unconventional and hectic ideas to reach the end objective of mayhem.

 ### -A tech stack.
We used phaser.js as our language of choice and coded it within the Codecademy as we had a base version created within that ide. This project was then uploaded to GitHub for publication and collaboration purposes.
