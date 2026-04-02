Roll-A-Ball-Game Project - All Version Updates;
====================================
  // Roll-A-Ball-Game Update V0.1 = Complete setting up the game; 

- I composed the new Unity project in editor as a RollABallGame,
- I created the setting and the characters using my own materials.
- Error messages = --
----------------------------------------------------------------------------------------
  //   Roll-A-Ball-Game Update V0.2 = Complete moving the player;

- I wrote the Playermovement code as  a "movementVector" context in VisualStudio but It gave an unknown context error,
- I realized I hadn’t explicitly assigned a value to the float in Script, it has been fixed with "movementX" and "movementY"
- I fixed the Movement speed with public float in Script. I used Public command because, I wanted to see also in Unity to take control of speed.
- Error messages = 2 (all resolved.)
----------------------------------------------------------------------------------------
   // Roll-A-Ball-Game Update V0.3 = Complete moving the camera;

- I changed the camera Rotation & Position Values to make Player look better with the platform.
- I created a separate script code to track the camera. (Instead of drag and drop method.)
- I fixed the camera stillness, Now it's following where player is going on the platfrom.
- Error messages = 1 (fixed as soon as possible.)
----------------------------------------------------------------------------------------
  //  Roll-A-Ball-Game Update V0.4 = Complete setting up the Play Area;

- I created the 4 different walls to make a certain area. (All of them well-positioned.)
- The player was passing through the walls, fixed with Box Collider part.
- The player was climbing the wall when it gained momentum. (Resolved with player mass balance.)
- Error messages = 3 (changed the player weight & speed.)
----------------------------------------------------------------------------------------
  // Roll-A-Ball-Game Update V0.5 = Complete creating collectibles;

- I created a new Prefab folder to apply the same principle to copies of a single object.
- I made 12 collectables around the character.
- Some of colletables weren't rotating on their own axis during the game. (Resolved with with precise 15-degree angles.)
- Error messages = 1 (fixed just spesific degree angles in Script.)
----------------------------------------------------------------------------------------
  // Roll-A-Ball-Game Update V1.0 = Roll-A-Ball-Game V1.0;

- Updated Player movement command in Script to get all collectibles.
- Added New Rigidbody component for Collectibles.
- I realized all Collectibles are falling downwards, (fixed with Kinematic part in Unity.)
- Added Displaying Scoreboard at the left corner.
- Added you win when you collect all the collectibles.
- Updated Collectible Infınıty golds. (I designed with Blender.)

