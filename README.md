# Challenge-02
Contains process to completing Challenge 02

## Creating your Base Kirby
Choose a sphere GameObject and place it on position (0,0,0) and keep scaling values at (1,1,1).  

Copy the sphere object once and scale it to act as Kirby’s foot, call it **‘Left Leg’**.  
The following are the scaling and position values for the standard Kirby’s left leg:

- **Position:**
  - x = -0.28  
  - y = -0.375  
  - z = 0.08  
  - Rotation in y-axis = 25˚  

- **Scaling:**
  - x = 0.6  
  - y = 0.4  
  - z = 0.9  

After setting these values, copy ‘Left Leg’ object and change x-position value to 0.28 and y-axis rotation to -25˚.  

Create another sphere GameObject for Kirby’s arm, call it **‘Right Arm’**. Use the following scaling and position values:

- **Position:**
  - x = 0.455  
  - y = -0.026  
  - z = 0.1  
  - Rotation in y-axis = -22˚  
  - Rotation in z-axis = -11˚  

- **Scaling:**
  - x = 0.5  
  - y = 0.3  
  - z = 0.3  

Like with Kirby’s legs, copy ‘Right Arm’ object and change x-position to -0.455, y-axis rotation to 22˚, and z-axis rotation to 11˚ to obtain symmetrical placing of arms.  

Finally, create a capsule GameObject for right eye called **‘Right Eye’**. These are the scaling and position values used for Kirby:

- **Position:**
  - x = 0.1  
  - y = 0.1  
  - z = 0.4625  
  - Rotation in x-axis = -11˚  

- **Scaling:**
  - x = 0.11  
  - y = 0.1125  
  - z = 0.1  

Copy ‘Right Eye’ object, call it **‘Left Eye’**, and change x-position to -0.1.  

Once you have finished creating your Main Kirby, drag it to Assets pane to create PreFab.  
The challenge asks to create four Kirby variants:  
- Leaf Kirby  
- Freeze Kirby  
- Sleeping Kirby  
- Mini Kirby  

---

## Leaf Kirby
Drag Main Kirby PreFab to Scene and position it at (0,0,0). Modify leg and arm objects position values to simulate a jumping animation.  

- **‘Right Leg’ Position:**
  - x = 0.215  
  - y = -0.325  
  - z = 0.26  
  - Rotation in x-axis = -16.325˚  
  - Rotation in y-axis = 25˚  

- **‘Left Leg’ Position:**
  - x = -0.2  
  - y = -0.33  
  - z = 0.225  
  - Rotation in x-axis = 139˚  
  - Rotation in y-axis = 32˚  
  - Rotation in z-axis = 45.5˚  

- **‘Right Arm’ Position:**
  - x = -0.2  
  - y = -0.33  
  - z = 0.225  
  - Rotation in x-axis = 139˚  
  - Rotation in y-axis = 32˚  
  - Rotation in z-axis = 45.5˚  

- **‘Left Arm’ Position:**
  - x = -0.47  
  - y = -0.015  
  - z = -0.115  
  - Rotation in x-axis = 24.6˚  
  - Rotation in y-axis = -65˚  
  - Rotation in z-axis = 6.5˚  

Copy ‘Left Eye’ capsule object to create left brow, call the new object **‘Left Brow’**.  
Change scaling and position values to the following:

- **‘Left Brow’**
  - **Position:**
    - x = -0.146  
    - y = 0.221  
    - z = 0.47  
    - Rotation in z-axis = 65˚  
  - **Scaling:**
    - x = 0.05  
    - y = 0.11  
    - z = 0.075  

For right brow, copy ‘Left Brow’ object and change x-position value to 0.146 and z-rotation to -65˚.  

Next various steps are related to creating the leaf crown, which is comprised of sphere objects with different scaling values.  
The scaling and position values for all sphere objects used are presented below.  

### Leaf Crown Objects
- **‘Main Leaf’**
  - Position: (0, 0.607, 0.448)  
  - Scaling: (0.5, 0.87, 0.05)  

- **‘Gem’**
  - Position: (0, 0.341, 0.467)  
  - Scaling: (0.21, 0.275, 0.05)  

- **‘Right Side Small Leaf’**
  - Position: (0.385, 0.258, 0.43)  
  - Rotation: z = -165˚  
  - Scaling: (0.52, 0.16, 0.05)  

- **‘Left Side Small Leaf’**
  - Position: (-0.385, 0.258, 0.43)  
  - Rotation: z = -165˚  
  - Scaling: (0.52, 0.16, 0.05)  

- **‘Right Main Leaf’**
  - Position: (0.225, 0.372, 0.388)  
  - Rotation: z = -44˚  
  - Scaling: (0.3775, 1.0625, 0.05)  

- **‘Left Main Leaf’**
  - Position: (-0.225, 0.372, 0.388)  
  - Rotation: z = 44˚  
  - Scaling: (0.3775, 1.0625, 0.05)  

- **‘Crown Right 1’**  
  - Position: (0.338, 0.497, 0.205)  
  - Rotation: x = -8˚, y = 62˚, z = -20˚  
  - Scaling: (0.333, 0.60, 0.05)  

- **‘Crown Right 2’**  
  - Position: (0.4, 0.5, -0.1)  
  - Rotation: x = -1˚, y = 90˚, z = -21˚  
  - Scaling: (0.325, 0.55, 0.05)  

- **‘Crown Right 3’**  
  - Position: (0.28, 0.45, -0.345)  
  - Rotation: x = -6˚, y = -46˚, z = 11˚  
  - Scaling: (0.375, 0.5, 0.05)  

- **‘Crown Left 1’**  
  - Position: (0.338, 0.497, 0.205)  
  - Rotation: x = -8˚, y = 62˚, z = -20˚  
  - Scaling: (0.333, 0.60, 0.05)  

- **‘Crown Left 2’**  
  - Position: (0.4, 0.5, -0.1)  
  - Rotation: x = -1˚, y = 90˚, z = -21˚  
  - Scaling: (0.325, 0.55, 0.05)  

- **‘Crown Left 3’**  
  - Position: (-0.28, 0.45, -0.345)  
  - Rotation: x = -6˚, y = -46˚, z = 11˚  
  - Scaling: (0.375, 0.5, 0.05)  

- **‘Crown Rear’**  
  - Position: (0, 0.47, -0.48)  
  - Rotation: x = -10˚  
  - Scaling: (0.35, 0.62, 0.05)  

- **Leaf Projectiles**  

---

## Freeze Kirby
Drag Main Kirby PreFab to Scene and position it at (0,0,0).  

Create a sphere GameObject, call it **‘Coat’**:

- **‘Coat’**
  - Position: (0,0,-0.13)  
  - Scaling: (1.3,1.2,1.15)  

Then create sphere objects for the coat shearling. Copy and paste this object with the following values to create a circle:

- **Scaling:** (0.35,0.35,0.35)  
- **Positions:**  
  - Sphere 1: (0, 0.5, 0.4)  
  - Sphere 2: (0.285, 0.35, 0.4)  
  - Sphere 3: (0.4, 0.06, 0.4)  
  - Sphere 4: (0.3, -0.225, 0.4)  
  - Sphere 5: (0, -0.33, 0.4)  
  - Sphere 6: (-0.3, 0.225, 0.4)  
  - Sphere 7: (-0.4, 0.06, 0.4)  
  - Sphere 8: (-0.285, 0.35, 0.4)  

---

## Sleeping Kirby
Drag Main Kirby PreFab to Scene and position it at (0,0,0).  

Modify leg, arm, and eye objects scaling and position values:

- **‘Right Eye’**  
  - Position: (0.1, 0.1, 0.47)  
  - Rotation: x = -14.5˚, y = 10˚, z = -3˚  
  - Scaling: (0.16, 0.0075, 0.045)  

- **‘Left Eye’**  
  - Position: (-0.1, 0.1, 0.47)  
  - Rotation: x = -14.5˚, y = -10˚, z = 3˚  
  - Scaling: (0.16, 0.0075, 0.045)  

- **‘Right Arm’**  
  - Position: (0.35, -0.15, 0.25)  
  - Rotation: x = -7˚, y = -70˚, z = 9˚  
  - Scaling: (0.57, 0.3, 0.4)  

- **‘Left Arm’**  
  - Position: (-0.35, -0.15, 0.25)  
  - Rotation: x = -7˚, y = 70˚, z = 9˚  
  - Scaling: (0.57, 0.3, 0.4)  

- **‘Right Leg’**  
  - Position: (0.285, -0.32, -0.385)  
  - Rotation: x = 135˚, y = -32˚, z = -25˚  
  - Scaling: (0.6, 0.4, 0.8)  

- **‘Left Leg’**  
  - Position: (-0.285, -0.32, -0.385)  
  - Rotation: x = 135˚, y = 32˚, z = 25˚  
  - Scaling: (0.6, 0.4, 0.8)  

### Hat
- **‘Rim’ (Capsule)**  
  - Position: (0, 0.1345, -0.0515)  
  - Rotation: x = -21˚  
  - Scaling: (1, 0.1, 1)  

- **‘Beanie’ (Sphere)**  
  - Position: (0, 0.15575, -0.0575)  
  - Rotation: x = -80˚  
  - Scaling: (0.92, 0.9867, 0.8218)  

- **‘Pom Pom’ (Sphere)**  
  - Position: (0, 0.35, -0.58)  
  - Scaling: (0.2,0.2,0.2)  

---

## Mini Kirby
Drag Main Kirby prefab, scale down to `(0.25,0.25,0.25)`.  

Adjust arms and legs for floating pose:

- **‘Right Leg’**  
  - Position: (0.2, -0.285, -0.4)  
  - Rotation: x = 145˚, y = -14˚, z = -25˚  
  - Scaling: (0.6, 0.4, 0.9)  

- **‘Left Leg’**  
  - Position: (-0.2, -0.285, -0.4)  
  - Rotation: x = 145˚, y = 14˚, z = 25˚  
  - Scaling: (0.6, 0.4, 0.9)  

- **‘Right Arm’**  
  - Position: (0.45, -0.025, 0.1)  
  - Rotation: y = 22˚, z = -11˚  
  - Scaling: (0.5, 0.3, 0.3)  

- **‘Left Arm’**  
  - Position: (-0.45, -0.025, -0.1)  
  - Rotation: y = -22˚, z = 11˚  
  - Scaling: (0.5, 0.3, 0.3)
