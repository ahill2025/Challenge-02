# Challenge-02
Contains process to completing Challenge 02

The task for challenge 02 is to create a Kirby model, along with variants and place them in a terrain built with a heightmap.
<br />
Before we proceed in creating our Kirbies, we're going to need colors to color our finished PreFab and Variants.
<br />
For this, we can go to the assets pane, right-click and select Create->Material.

<img width="369" height="800" alt="New Material" src="https://github.com/user-attachments/assets/a7973f05-d89a-45a6-b490-e652a8f8b225" />

<br><br>
Our project required the following colors:
- Colors:
  - Red
  - Pink
  - Black
  - White
  - Green
  - Indigo (modified with slider)
  - Pale Green
  - Chartreuse Green
  - Yellow-Green

Now that our colors are set up, begin by creating a sphere GameObject and place it on position (0,0,0) and keep scaling values at (1,1,1).  Copy the sphere object once and scale it to act as the leg, call it ‘Left Leg’.  


All GameObjects are children to the main body (in this case, 'Main Kirby'), thus scaling and position values are dependent of the former.Drag your 'Pink' material to color your object.


The following are the scaling and position values for the 'Main Kirby''s left leg:

- Position:
  - x = -0.28  
  - y = -0.375  
  - z = 0.08  
  - Rotation in y-axis = 25˚  

- Scaling:
  - x = 0.6  
  - y = 0.4  
  - z = 0.9
 
- Color:
  - Red 
<br>
After setting these values, copy ‘Left Leg’ object, call it 'Right Leg', and change x-position value to 0.28 and y-axis rotation to -25˚.  


Create another sphere GameObject for the arm, call it ‘Right Arm’. Use the following scaling and position values:

- Position:
  - x = 0.455  
  - y = -0.026  
  - z = 0.1  
  - Rotation in y-axis = -22˚  
  - Rotation in z-axis = -11˚  

- Scaling:
  - x = 0.5  
  - y = 0.3  
  - z = 0.3
 
- Color:
  - Pink
<br>
Copy the ‘Right Arm’ object and change x-position to -0.455, y-axis rotation to 22˚, and z-axis rotation to 11˚ to obtain symmetrical placing of arms.  

Create capsule GameObject for right eye called ‘Right Eye’. These are their the scaling and position values:

- Position:
  - x = 0.1  
  - y = 0.1  
  - z = 0.4625  
  - Rotation in x-axis = -11˚  

- Scaling:
  - x = 0.11  
  - y = 0.1125  
  - z = 0.1  
- Color:
  - Black
 

Copy ‘Right Eye’ object, call it ‘Left Eye', and change x-position to -0.1. 

Finally, create a sphere object for the right eye's pupil, call it 'Right Pupil'.  Apply the following inputs to position values: 
- Position:
  - x = 0.1  
  - y = 0.13  
  - z = 0.492  
  - Rotation in x-axis = -11˚  

- Scaling:
  - x = 0.05 
  - y = 0.1  
  - z = 0.05
- Color:
  - White
 

Copy the 'Right Pupil' object, calling it 'Left Pupil' and change the x-position value to -0.1.  

<img width="1116" height="656" alt="Main Kirby" src="https://github.com/user-attachments/assets/1b049686-037e-48ec-8f07-ba219fd1d66e" />

Once you have finished creating your 'Main Kirby', drag it to Assets pane to create PreFab. 
The challenge asks to create four Kirby variants:  
- Leaf Kirby  
- Freeze Kirby  
- Sleeping Kirby  
- Mini Kirby

---

**Leaf Kirby**

Drag 'Main Kirby' PreFab to Scene and position it at (0,0,0). Modify leg and arm objects position values to simulate a jumping animation.  

- ‘Right Leg’ Position:
  - x = 0.215  
  - y = -0.325  
  - z = 0.26  
  - Rotation in x-axis = -16.325˚  
  - Rotation in y-axis = 25˚
  - Color: Red

- ‘Left Leg’ Position:
  - x = -0.2  
  - y = -0.33  
  - z = 0.225  
  - Rotation in x-axis = 139˚  
  - Rotation in y-axis = 32˚  
  - Rotation in z-axis = 45.5˚
  - Color: Red 

- ‘Right Arm’ Position:
  - x = -0.2  
  - y = -0.33  
  - z = 0.225  
  - Rotation in x-axis = 139˚  
  - Rotation in y-axis = 32˚  
  - Rotation in z-axis = 45.5˚
  - Color: Pink

- ‘Left Arm’ Position:
  - x = -0.47  
  - y = -0.015  
  - z = -0.115  
  - Rotation in x-axis = 24.6˚  
  - Rotation in y-axis = -65˚  
  - Rotation in z-axis = 6.5˚
  - Color: Pink

Copy ‘Left Eye’ capsule object to create left brow, call the new object ‘Left Brow’.  
Change scaling and position values to the following:

- ‘Left Brow’
  - Position:
    - x = -0.146  
    - y = 0.221  
    - z = 0.47  
    - Rotation in z-axis = 65˚  
  - Scaling:
    - x = 0.05  
    - y = 0.11  
    - z = 0.075
  - Color: Black

Create 'Right Brow' by copying the ‘Left Brow’ object and changing its x-position value to 0.146, along with z-rotation to -65˚.  
To create the pupils, follow the same instructions detailed above for 'Main Kirby'

Next steps are related to creating the leaf crown, which is comprised of sphere objects with different scaling values.  
The scaling and position values for all sphere objects used are presented below.  

**Leaf Crown Objects**

- ‘Main Leaf’  
  - Position:  
    - x = 0  
    - y = 0.607  
    - z = 0.448  
  - Scaling:  
    - x = 0.5  
    - y = 0.87  
    - z = 0.05
   
  - Color: Green 

- ‘Gem’  
  - Position:  
    - x = 0  
    - y = 0.341  
    - z = 0.467  
  - Scaling:  
    - x = 0.21  
    - y = 0.275  
    - z = 0.05
   
  - Color: Chartreuse Green 

- ‘Right Side Small Leaf’  
  - Position:  
    - x = 0.385  
    - y = 0.258  
    - z = 0.43  
    - Rotation in z-axis = -165˚  
  - Scaling:  
    - x = 0.52  
    - y = 0.16  
    - z = 0.05
   
  - Color: Green

- ‘Left Side Small Leaf’  
  - Position:  
    - x = -0.385  
    - y = 0.258  
    - z = 0.43  
    - Rotation in z-axis = -165˚  
  - Scaling:  
    - x = 0.52  
    - y = 0.16  
    - z = 0.05
   
  - Color: Green

- ‘Right Main Leaf’  
  - Position:  
    - x = 0.225  
    - y = 0.372  
    - z = 0.388  
    - Rotation in z-axis = -44˚  
  - Scaling:  
    - x = 0.3775  
    - y = 1.0625  
    - z = 0.05
   
  - Color: Yellow-Green 

- ‘Left Main Leaf’  
  - Position:  
    - x = -0.225  
    - y = 0.372  
    - z = 0.388  
    - Rotation in z-axis = 44˚  
  - Scaling:  
    - x = 0.3775  
    - y = 1.0625  
    - z = 0.05
   
  - Color: Yellow-Green 

- ‘Crown Right 1’  
  - Position:  
    - x = 0.338  
    - y = 0.497  
    - z = 0.205  
    - Rotation in x-axis = -8˚  
    - Rotation in y-axis = 62˚  
    - Rotation in z-axis = -20˚  
  - Scaling:  
    - x = 0.333  
    - y = 0.60  
    - z = 0.05
   
  - Color: Green
 

- ‘Crown Right 2’  
  - Position:  
    - x = 0.4  
    - y = 0.5  
    - z = -0.1  
    - Rotation in x-axis = -1˚  
    - Rotation in y-axis = 90˚  
    - Rotation in z-axis = -21˚  
  - Scaling:  
    - x = 0.325  
    - y = 0.55  
    - z = 0.05
   
  - Color: Yellow-Green

- ‘Crown Right 3’  
  - Position:  
    - x = 0.28  
    - y = 0.45  
    - z = -0.345  
    - Rotation in x-axis = -6˚  
    - Rotation in y-axis = -46˚  
    - Rotation in z-axis = 11˚  
  - Scaling:  
    - x = 0.375  
    - y = 0.5  
    - z = 0.05
   
  - Color: Green

- ‘Crown Left 1’  
  - Position:  
    - x = 0.338  
    - y = 0.497  
    - z = 0.205  
    - Rotation in x-axis = -8˚  
    - Rotation in y-axis = 62˚  
    - Rotation in z-axis = -20˚  
  - Scaling:  
    - x = 0.333  
    - y = 0.60  
    - z = 0.05
   
  - Color: Green

- ‘Crown Left 2’  
  - Position:  
    - x = 0.4  
    - y = 0.5  
    - z = -0.1  
    - Rotation in x-axis = -1˚  
    - Rotation in y-axis = 90˚  
    - Rotation in z-axis = -21˚  
  - Scaling:  
    - x = 0.325  
    - y = 0.55  
    - z = 0.05
   
  - Color: Yellow-Green

- ‘Crown Left 3’  
  - Position:  
    - x = -0.28  
    - y = 0.45  
    - z = -0.345  
    - Rotation in x-axis = -6˚  
    - Rotation in y-axis = -46˚  
    - Rotation in z-axis = 11˚  
  - Scaling:  
    - x = 0.375  
    - y = 0.5  
    - z = 0.05
   
  - Color: Green

- ‘Crown Rear’  
  - Position:  
    - x = 0  
    - y = 0.47  
    - z = -0.48  
    - Rotation in x-axis = -10˚  
  - Scaling:  
    - x = 0.35  
    - y = 0.62  
    - z = 0.05
   
  - Color:  Yellow-Green
<br>
For the leaf projectiles, create an spherical object called 'Leaf Projectile' resembling those of the crown pieces and add a stem using a cube object called 'Stem'.  Make the 'Stem' object a child object to 'Leaf Projectile' and modify they y-position value to -0.303. These were the scaling values for the projectiles, position values are not included since these are not as restricting (can be loose with placement):

- ‘Projectile’  
  - Scaling:  
    - x = 0.3  
    - y = 0.5  
    - z = 0.025
   
- ‘Stem’   
  - Scaling:  
    - x = 0.1  
    - y = 0.057  
    - z = 0.2 
Color for both is Green.

<img width="1118" height="657" alt="Leaf Kirby" src="https://github.com/user-attachments/assets/497c2be8-6729-4796-a590-c8be67a10072" />

---
**Freeze Kirby**
<br>
Drag Main Kirby PreFab to Scene and position it at (0,0,0).  
<br>
Create a sphere GameObject, call it ‘Coat’:  
- Position:  
  - x = 0  
  - y = 0  
  - z = -0.13  
- Scaling:  
  - x = 1.3  
  - y = 1.2  
  - z = 1.15
 
- Color: Indigo (including both arm objects)
<br>
Then create sphere objects for coat shearling. Copy and paste this object with the following scaling values and position them to create a circle encompassing your Freeze Kirby.  

- Scaling Values:  
  - x = 0.35  
  - y = 0.35  
  - z = 0.35  

- Position Values:  
  - ‘Sphere 1’  
    - x = 0  
    - y = 0.5  
    - z = 0.4  
  - ‘Sphere 2’  
    - x = 0.285  
    - y = 0.35  
    - z = 0.4  
  - ‘Sphere 3’  
    - x = 0.4  
    - y = 0.06  
    - z = 0.4  
  - ‘Sphere 4’  
    - x = 0.3  
    - y = -0.225  
    - z = 0.4  
  - ‘Sphere 5’  
    - x = 0  
    - y = -0.33  
    - z = 0.4  
  - ‘Sphere 6’  
    - x = -0.3  
    - y = 0.225  
    - z = 0.4  
  - ‘Sphere 7’  
    - x = -0.4  
    - y = 0.06  
    - z = 0.4  
  - ‘Sphere 8’  
    - x = -0.285  
    - y = 0.35  
    - z = 0.4
   
  - Color for sphere objects is White
<br>
<img width="1117" height="659" alt="Freeze Kirby" src="https://github.com/user-attachments/assets/748d1053-5df9-4823-b175-35479da01431" />

---
**Sleeping Kirby**
<br>
Drag Main Kirby PreFab to Scene and position it at (0,0,0).  
Modify leg, arm, and eye objects scaling and position values to design Kirby sleeping.    
<br>
- ‘Right Eye’  
  - Position:  
    - x = 0.1  
    - y = 0.1  
    - z = 0.47  
    - Rotation in x-axis = -14.5˚  
    - Rotation in y-axis = 10˚  
    - Rotation in z-axis = -3˚  
  - Scaling:  
    - x = 0.16  
    - y = 0.0075  
    - z = 0.045
   
  - Color: Black 

- ‘Left Eye’  
  - Position:  
    - x = -0.1  
    - y = 0.1  
    - z = 0.47  
    - Rotation in x-axis = -14.5˚  
    - Rotation in y-axis = -10˚  
    - Rotation in z-axis = 3˚  
  - Scaling:  
    - x = 0.16  
    - y = 0.0075  
    - z = 0.045
   
  - Color: Black
   
<br>
To create the pupils, follow the same instructions as with 'Main Kirby'
<br>

- ‘Right Arm’  
  - Position:  
    - x = 0.35  
    - y = -0.15  
    - z = 0.25  
    - Rotation in x-axis = -7˚  
    - Rotation in y-axis = -70˚  
    - Rotation in z-axis = 9˚  
  - Scaling:  
    - x = 0.57  
    - y = 0.3  
    - z = 0.4
   
  - Color: Pink

- ‘Left Arm’  
  - Position:  
    - x = -0.35  
    - y = -0.15  
    - z = 0.25  
    - Rotation in x-axis = -7˚  
    - Rotation in y-axis = 70˚  
    - Rotation in z-axis = 9˚  
  - Scaling:  
    - x = 0.57  
    - y = 0.3  
    - z = 0.4
   
  - Color: Pink

- ‘Right Leg’  
  - Position:  
    - x = 0.285  
    - y = -0.32  
    - z = -0.385  
    - Rotation in x-axis = 135˚  
    - Rotation in y-axis = -32˚  
    - Rotation in z-axis = -25˚  
  - Scaling:  
    - x = 0.6  
    - y = 0.4  
    - z = 0.8
   
  - Color: Red

- ‘Left Leg’  
  - Position:  
    - x = -0.285  
    - y = -0.32  
    - z = -0.385  
    - Rotation in x-axis = 135˚  
    - Rotation in y-axis = 32˚  
    - Rotation in z-axis = 25˚  
  - Scaling:  
    - x = 0.6  
    - y = 0.4  
    - z = 0.8
   
  - Color: Red
 
<br>
Create a capsule game object for hat rim.  Rename the object to ‘Rim’.  Following are the scaling and position values:


- ‘Rim’
  - Position:  
    - x = 0  
    - y = 0.1345  
    - z = -0.0515  
    - Rotation in x-axis = -21˚  
  - Scaling:  
    - x = 1  
    - y = 0.1  
    - z = 1


Next, create the beanie by creating a sphere game object.  Input the position and scaling values shown below:

- ‘Beanie’ 
  - Position:  
    - x = 0  
    - y = 0.15575  
    - z = -0.0575  
    - Rotation in x-axis = -80˚  
  - Scaling:  
    - x = 0.92  
    - y = 0.9867  
    - z = 0.8218
   

Now, create the game object called ‘Pom Pom’ for the little ball above the beanie with the following position and scaling values.


- ‘Pom Pom’ (Sphere)  
  - Position:  
    - x = 0  
    - y = 0.35  
    - z = -0.58  
  - Scaling:  
    - x = 0.2  
    - y = 0.2  
    - z = 0.2  

You can simulate snoring bubbles by simply creating symmetrical spherical objects and placing them to indicate your Kirby variant is asleep.  
<img width="1118" height="656" alt="Sleeping Kirby" src="https://github.com/user-attachments/assets/b94fb0a1-330e-4fa5-8108-11361c0c6332" />

---
**Mini Kirby**

For the last Kirby variant, take the Main Kirby prefab, drag it onto the scene and scale all values down to (0.25, 0.25, 0.25).  
Next, modify arm and leg position and scaling values to design a floating (jumping) Kirby.  

- ‘Right Leg’  
  - Position:  
    - x = 0.2  
    - y = -0.285  
    - z = -0.4  
    - Rotation in x-axis = 145˚  
    - Rotation in y-axis = -14˚  
    - Rotation in z-axis = -25˚  
  - Scaling:  
    - x = 0.6  
    - y = 0.4  
    - z = 0.9  

- ‘Left Leg’  
  - Position:  
    - x = -0.2  
    - y = -0.285  
    - z = -0.4  
    - Rotation in x-axis = 145˚  
    - Rotation in y-axis = 14˚  
    - Rotation in z-axis = 25˚  
  - Scaling:  
    - x = 0.6  
    - y = 0.4  
    - z = 0.9  

- ‘Right Arm’  
  - Position:  
    - x = 0.45  
    - y = -0.025  
    - z = 0.1  
    - Rotation in y-axis = 22˚  
    - Rotation in z-axis = -11˚  
  - Scaling:  
    - x = 0.5  
    - y = 0.3  
    - z = 0.3  

- ‘Left Arm’  
  - Position:  
    - x = -0.45  
    - y = -0.025  
    - z = -0.1  
    - Rotation in y-axis = -22˚  
    - Rotation in z-axis = 11˚  
  - Scaling:  
    - x = 0.5  
    - y = 0.3  
    - z = 0.3
   
<img width="1122" height="656" alt="Mini Kirby" src="https://github.com/user-attachments/assets/e65b2c1b-9a82-4c01-93ea-cbd9a4ae9181" />

---

The next step in our challenge is to create a terrain and populate it with our Kirby variants.  Our terrain will be created using a heighmap of a section in Puerto Rico.  

First, we need a grayscale image of the terrain to be copied.  For this, Tangram Heightmapper application is used.  
<img width="1538" height="815" alt="Download Terrain Tools" src="https://github.com/user-attachments/assets/fe190c81-ad90-44b4-b5dc-de681e33a223" />
<br><br>
Once you export the image, go to your Unity project and drag the downloaded image to your assets pane.  Once done, you'll need to download Terrain Tools using the Package Management tab.  



After installing, go to Windows -> Terrain -> Terrain toolbox and a new window will appear.  Here, set the length and width with the following values:
- Length = 250
- Width = 250
- Height = 250


<br>
<img width="816" height="676" alt="Terrain Tools Import" src="https://github.com/user-attachments/assets/984cbbe5-cbd6-41ad-adab-8da8c61fcb6c" />
<br>

Then on the 'Import Heightmap' tab, click the select buttoon and choose your recently dragged image.  Finally, click create to see your new terrain!  

<br>
<img width="1292" height="1029" alt="Grayscale" src="https://github.com/user-attachments/assets/acadd090-9f13-4091-85d8-8067eb6e29df" />
<br>
<img width="602" height="612" alt="Grayscale Mold" src="https://github.com/user-attachments/assets/5988205d-fd05-4e83-b2d9-0391203cd49d" />
<br>

Add some texture to your terrain by clicking on your new Terrain object.  On the Inspector pane, click 'Paint Terrain' -> 'Paint Texture' and go down to 'Layers'.  Once there, add two layers, one for the base of terrain and the other as an additive to brush on your terrain.  

<br><br>
Style terrain at your discretion and proceed to place your Kirbies in your newly created world.  
<br>
<img width="1120" height="656" alt="Freeze and Mini Kirby" src="https://github.com/user-attachments/assets/1f0eba1b-cd87-4fe7-9d5f-12ab53771e15" />
<br><br><br>
<img width="1118" height="655" alt="Leaf and Sleeping Kirby" src="https://github.com/user-attachments/assets/c3afa972-9316-4849-ac29-27843ec9dddb" />



