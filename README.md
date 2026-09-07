# GAME351-Unity 

Using Built-in Render Pipeline 

### **Planet959** 

Implementations of Choice Components:
1. Small Village
2. Areas of Water

### **Authors**



**Santana Madero (nyxnavi)**

Created the rolling hills and divots, mountains and lake location using Paint Terrain

Gave cliffs on mountains their own texture, grass land, and dirt using *Free Fantasy Terrain Textures*: **3DH FTT Dirt_001 2k, 3DH FTT Grass_002 Grass_oo1b 2k, 3DH Ftt Cliff_001 4l**



\----------------------------------------------------------------------------------------------

**Nathan Holsinger (majorbigbear)**	

Tree prefabs were from *European Forests - Realistic Trees*: **Weeping_Willow 3, Chestnut (3,8,5), Birch Group 2** And I duplicated, rotated and uniquely placed all tree groups to ensure accuracy to the ground

The village building prefabs were from *Medieval Town Exteriors*: **Building_(b,c,d,f), Well, Fence** I duplicated the fence with accuracy to the ground**

Added more realistic embrasures around the castle wall

Added dirt terrain around walking paths to simulate travel

Added the following tools to bring a little more life to the world from *Gardening Tools Pack - 26 PBR objects*: **Axe_001, Broom_001, Shovel_003**

Added some **Wooden Box 01** next to a house and **Handcart** from *RPG Medieval Props Pack 01* next to the tool shed

Cleaned up some of the terrain using *Procedural Terrain Painter | FREE - Automatic Terrain Texturing* as well as added grass texture around the floors from *Terrain Asset Pack | Terrain Sample*

Took the water asset with shader from *Procedural Water Shader* It acts as an object that you walk on and not something you can actually get into

Wooden rowboat from *Wooden row boat - Game Asset*: **BoatWood** and placed it on the shoreline of the small pond

\----------------------------------------------------------------------------------------------

**Chris Jones (chrisj\_04123)**

The castle was built using ProBuilder. Cubes were used to create wall segments. Cylinders were used to create logs for the wood catwalk around the castle walls.

The outside catwalk is accessed using ramps created from logs.

The castle entrance is a door object.  

The keep was also created with ProBuilder using cubes, doors and stairs. To allow Jammo to climb the stairs, an invisible plane was added to each set of stairs.

Some of the textures were difficult to apply aesthetically and look irregular when viewed in game.

Merchant prefabs were created using prefabs from the *RPG Medieval Props Pack 01*: **Wooden\_Bucket\_1, Vase\_5, Clay\_Mug, Clay Pot, Wooden Box 01, Vase\_3, Barrel 01, Crate\_02,**

**Tent and Handcart**. 



**Assets used:**
Outer Castle Walls and Catwalk pillars: *Free Fantasy Terrain Textures* - **Wall 01**

Catwalk and Ramp Logs: *Hand Painted Seamless Wood Texture Vol - 6* - **Spruce**

Castle Entry: *Free Fantasy Terrain Textures* - **Wall 09**

Keep Entry: *Free Fantasy Terrain Textures* - **Wall 03b**

Keep and Tower Walls: *Free Fantasy Terrain Textures* - **Wall 03**

Keep Floor and Inner Catwalk Support: *Stone Floor Textures* - **New Material**



\----------------------------------------------------------------------------------------------

**Carrington Jones** (carrington-jones)

Follow camera set up using the existing Main Camera in the scene. Main camera placed under Robot_Player in the project hierarchy. The follow effect was created using Unity's parent-child relationship.

Version control implemented by using Github. The Github Unity project template was used with extensive .gitignore file to avoid uploading Unity-generated folders and files.


\----------------------------------------------------------------------------------------------



##### **Asset Packages:**

FREE Fantasy Terrain Textures

European Forests - Realistic Trees

Procedural Water Shader

Stone Floor Textures

18 High Resolution Wall Textures

RPG Medieval Props Pack 01

Hand Painted Seamless Wood Texture Vol - 6

Gardening Tools Pack - 26 PBR objects

Medieval Town Exteriors

Terrain Asset Pack | Terrain Sample

Free Fantasy Terrain Textures

Wooden row boat - Game Asset





Installation instructions for editor:
1. Download and unzip the folder
2. Open up Unity Hub and ensure version 2021.3.5f1 is installed
3. In the top right hand corner click on the Add drop down and select "Add project from disk"
4. Navigate to the unzipped downloaded folder
5. Double click on the project and it will open
6. In the folder hierarchy at the bottom left of the screen, you will see an Assets folder
7. In the Assets folder is another folder labelled Scenes
8. Drag and drop Planet959 scene into the object hierarchy in the top left of the screen
9. Remove the Default scene if it is present
10. Click File in the top left hand corner and click on Build and Run