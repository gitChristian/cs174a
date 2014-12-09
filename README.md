CS174a_TermProject
==================

Term Project for CS 174a

Team 9
Team Members: Joey Gomez-Benito, Chris Nersesyan, Zhen Liu, Yifan Wang

Roles and Implementation:

Joey - My main roles in this project were creating the environment, working on the controls for the plane, creating the scoring, making the crash popup menu, reloading the world, making the game fullscreen, css styling, and overall bug fixes. The environment is a giant cube with a texture map on the floor and the ceiling. The building and cubes are both translated back at the same rate. The controls were made by carefully rotating and translating the world and then rotating back. The scoring system was made through the use of javascript. The menu was made using HTML, CSS, javascript and jQuery. On restart, the world gets translated back into its original starting position. I also worked on fixing many bugs. One of the bigger ones I helped fix was loading the plane. 

To run the program, open index.html.
Right now, it only works on internet explorer and (75% sure) Safari.
Use the arrow keys to move around the world and try to dodge the buildings. Have fun!

We implemented lighting only on the plane.
There is also sound. This can be toggled on the menu that appears when you crash.

Advanced Topics:
Collision detection
Bump mapping on the floor

We had some wierd effects when we ran this on a mac with retina display on safari. The floor flickered when we implemented bump mapping and the plane had a diamond-like effect.

It works well on windows with internet explorer.
