CS174a_TermProject
==================

Term Project for CS 174a

Team 9
Team Members: Joey Gomez-Benito, Chris Nersesyan, Zhen Liu, Yifan Wang

Roles and Implementation:

Joey - My main roles in this project were creating the environment, working on the controls for the plane, creating the scoring, making the crash popup menu, reloading the world, making the game fullscreen, css styling, and overall bug fixes. The environment is a giant cube with a texture map on the floor and the ceiling. The building and cubes are both translated back at the same rate. The controls were made by carefully rotating and translating the world and then rotating back. The scoring system was made through the use of javascript. The menu was made using HTML, CSS, javascript and jQuery. On restart, the world gets translated back into its original starting position. I also worked on fixing many bugs. One of the bigger ones I helped fix was loading the plane. 

Yifan - My major rule in this project is to design a plane model from scratch. The plane consists of more than twenty vertices whose coordinates are hand calculated from two original design photo of stealth fighter F-117. Relative X-Y and Y-Z coordinates are measured by calculating relative pixels distance between them and are later transformed, inverted and normalized. Each faces of the plane is then determined and 102 indices are designed to provide careful triangulation of the plane. The plane model is finally tested and added light effect under help of Joey and Chris. Zhen provides many useful advice too. It’s a really nice team to work with.

Zhen - My major role in this project is to implement the collision detection algorithm. All functions related to collision detection is implemented by me without using any library. The algorithm uses axis-aligned bounding box to represent objects including the plane. If a potential collision is detected, the program performs a thorough check based on intersection test between triangles to precisely judge whether the collision indeed happened. The algorithm is refined so that it does not consume much computation power. I also worked on generating normal vectors for the plane model by implementing a function calculating all normal vectors needed based on the input vertices. 

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
