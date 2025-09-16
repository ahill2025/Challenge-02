# Challenge-02
Contains process to completing Challenge 02

Creating your base Kirby:
Choose a sphere GameObject and place it on position (0,0,0) and keep scaling values at (1,1,1).  Copy the sphere object once and scale it to act as Kirby’s foot, call it ‘Left Leg’.  The following are the scaling and position values for the standard Kirby’s left leg.
  *	Position:
    -	x = -0.28
    -	y = -0.375
    -	z = 0.08
    -	Rotation in y-axis = 25˚
  *	Scaling:
    -	x = 0.6
    -	y = 0.4
    -	z = 0.9
   

After setting these values, copy ‘Left Leg’ object and change x-position value to 0.28 and y-axis rotation to -25˚.  Create another sphere GameObject for Kirby’s arm, call it ‘Right Arm’.  Use the following scaling and position values:
  *	 Position:
   -	x = 0.455
   -	y = -0.026
   -	z = 0.1
   -	Rotation in y-axis = -22˚
   -	Rotation in z-axis = -11˚
  *	Scaling:
   -	x = 0.5
   -	y = 0.3
   -	z = 0.3


Like with Kirby’s legs, copy ‘Right Arm’ object and change x-position to -0.455, y-axis rotation to 22˚, and z-axis rotation to 11˚ to obtain symmetrical placing of arms.  Finally, create a capsule GameObject for right eye called ‘Right Eye’.  These are the scaling and position values used for Kirby:
 *	Position:
  -	x = 0.1
  -	y = 0.1
  -	z = 0.4625
  -	Rotation in x-axis = -11˚
 *	Scaling:
  -	x = 0.11
  -	y = 0.1125
  -	z = 0.1


Copy ‘Right Eye’ object, call it ‘Left Eye’, and change x-position to -0.1.

Once you have finished creating your Main Kirby, drag it to Assets pane to create PreFab.  The challenge asks to create four Kirby variants.  The variants created were Leaf Kirby, Freeze Kirby, Sleeping Kirby, and Mini Kirby.  


Leaf Kirby:


Drag Main Kirby PreFab to Scene and position it at (0,0,0).  Modify leg and arm objects position values to simulate a jumping animation.  

 *	‘Right Leg’ Position:
  -	x = 0.215
  -	y = -0.325
  -	z = 0.26
  -	Rotation in x-axis = -16.325˚
  -	Rotation in y-axis = 25˚
 *	‘Left Leg’ Position:
  -	x = -0.2
  -	y = -0.33
  -	z = 0.225
  -	Rotation in x-axis = 139˚
  -	Rotation in y-axis = 32˚
  -	Rotation in z-axis = 45.5˚
 *	‘Right Arm’ Position:
  -	x = -0.2
  -	y = -0.33
  -	z = 0.225
  -	Rotation in x-axis = 139˚
  -	Rotation in y-axis = 32˚
  -	Rotation in z-axis = 45.5˚
 *	‘Left Arm’ Position:
  -	x = -0.47
  -	y = -0.015
  -	z = -0.115
  -	Rotation in x-axis = 24.6˚
  -	Rotation in y-axis = -65˚
  -	Rotation in z-axis = 6.5˚


Copy ‘Left Eye’ capsule object to create left brow, call the new object ‘Left Brow’.  Change scaling and position values to the following:
 *	‘Left Brow’ 
  -	Position:
   *	x = -0.146
   *	y = 0.221
   *	z = 0.47
   *	Rotation in z-axis = 65˚
  -	Scaling:
   *	x = 0.05
   * y = 0.11
   *	z = 0.075
For right brow, copy ‘Left Brow’ object and change x-position value to 0.146 and z-rotation to -65˚.  
Next various steps are related to creating the leaf crown, which is comprised of sphere objects with different scaling values.  The scaling and position values for all sphere objects used are presented below.  Photo showcasing the Leaf Kirby variant will contain all additional sphere objects for the crown.  
-	‘Main Leaf’ 
o	Position:
	x = 0
	y = 0.607
	z = 0.448
o	Scaling:
	x = 0.5
	y = 0.87
	z = 0.05
-	‘Gem’ 
o	Position:
	x = 0
	y = 0.341
	z = 0.467
o	Scaling:
	x = 0.21
	y = 0.275
	z = 0.05
-	‘Right Side Small Leaf’ 
o	Position:
	x = 0.385
	y = 0.258
	z = 0.43
	Rotation in z-axis = -165˚
o	Scaling:
	x = 0.52
	y = 0.16
	z = 0.05
-	‘Left Side Small Leaf’ 
o	Position:
	x = -0.385
	y = 0.258
	z = 0.43
	Rotation in z-axis = -165˚
o	Scaling:
	x = 0.52
	y = 0.16
	z = 0.05
-	‘Right Main Leaf’ 
o	Position:
	x = 0.225
	y = 0.372
	z = 0.388
	Rotation in z-axis = -44˚
o	Scaling:
	x = 0.3775
	y = 1.0625
	z = 0.05
-	‘Left Main Leaf’ 
o	Position:
	x = -0.225
	y = 0.372
	z = 0.388
	Rotation in z-axis = 44˚
o	Scaling:
	x = 0.3775
	y = 1.0625
	z = 0.05


-	‘Crown Right 1’ 
o	Position:
	x = 0.338
	y = 0.497
	z = 0.205
	Rotation in x-axis = -8˚
	Rotation in y-axis = 62˚
	Rotation in z-axis = -20˚
o	Scaling:
	x = 0.333
	y = 0.60
	z = 0.05
-	‘Crown Right 2’ 
o	Position:
	x = 0.4
	y = 0.5
	z = -0.1
	Rotation in x-axis = -1˚
	Rotation in y-axis = 90˚
	Rotation in z-axis = -21˚
o	Scaling:
	x = 0.325
	y = 0.55
	z = 0.05
-	‘Crown Right 3’ 
o	Position:
	x = 0.28
	y = 0.45
	z = -0.345
	Rotation in x-axis = -6˚
	Rotation in y-axis = -46˚
	Rotation in z-axis = 11˚
o	Scaling:
	x = 0.375
	y = 0.5
	z = 0.05
-	‘Crown Left 1’ 
o	Position:
	x = 0.338
	y = 0.497
	z = 0.205
	Rotation in x-axis = -8˚
	Rotation in y-axis = 62˚
	Rotation in z-axis = -20˚
o	Scaling:
	x = 0.333
	y = 0.60
	z = 0.05
-	‘Crown Left 2’ 
o	Position:
	x = 0.4
	y = 0.5
	z = -0.1
	Rotation in x-axis = -1˚
	Rotation in y-axis = 90˚
	Rotation in z-axis = -21˚
o	Scaling:
	x = 0.325
	y = 0.55
	z = 0.05
-	‘Crown Left 3’ 
o	Position:
	x = -0.28
	y = 0.45
	z = -0.345
	Rotation in x-axis = -6˚
	Rotation in y-axis = -46˚
	Rotation in z-axis = 11˚
o	Scaling:
	x = 0.375
	y = 0.5
	z = 0.05
-	‘Crown Rear’ 
o	Position:
	x = 0
	y = 0.47
	z = -0.48
	Rotation in x-axis = -10˚
o	Scaling:
	x = 0.35
	y = 0.62
	z = 0.05
-	Leaf Projectiles

Freeze Kirby:
Drag Main Kirby PreFab to Scene and position it at (0,0,0).   Create a sphere GameObject, call it ‘Coat’ and input these scaling and position values:
-	‘Coat’
o	 Position:
	x = 0
	y = 0
	z = -0.13
o	Scaling:
	x = 1.3
	y = 1.2
	z = 1.15
Then create sphere objects for the coat shearling.  Copy and paste this object with the following scaling values and position them to create a circle encompassing your Freeze Kirby. 
-	Scaling Values:
o	x = 0.35
o	y = 0.35
o	z = 0.35
-	Position Values: 
o	‘Sphere 1’:
	x = 0
	y = 0.5
	z = 0.4
o	‘Sphere 2’:
	x = 0.285
	y = 0.35
	z = 0.4
o	‘Sphere 3’:
	x = 0.4
	y = 0.06
	z = 0.4
o	‘Sphere 4’:
	x = 0.3
	y = -0.225
	z = 0.4
o	‘Sphere 5’:
	x = 0
	y = -0.33
	z = 0.4
o	‘Sphere 6’:
	x = -0.3
	y = 0.225
	z = 0.4
o	‘Sphere 7’:
	x = -0.4
	y = 0.06
	z = 0.4
o	‘Sphere 8’:
	x = -0.285
	y = 0.35
	z = 0.4
Sleeping Kirby:
Drag Main Kirby PreFab to Scene and position it at (0,0,0).  Modify leg, arm, and eye objects scaling and position values to design Kirby sleeping.    
-	‘Right Eye’ 
o	Position:
	x = 0.1
	y = 0.1
	z = 0.47
	Rotation in x-axis = -14.5˚
	Rotation in y-axis = 10˚
	Rotation in z-axis = -3˚
o	Scaling:
	x = 0.16
	y = 0.0075
	z = 0.045
-	‘Left Eye’ 
o	Position:
	x = -0.1
	y = 0.1
	z = 0.47
	Rotation in x-axis = -14.5˚
	Rotation in y-axis = -10˚
	Rotation in z-axis = 3˚
o	Scaling:
	x = 0.16
	y = 0.0075
	z = 0.045
-	‘Right Arm’ 
o	Position:
	x = 0.35
	y = -0.15
	z = 0.25
	Rotation in x-axis = -7˚
	Rotation in y-axis = -70˚
	Rotation in z-axis = 9˚
o	Scaling:
	x = 0.57
	y = 0.3
	z = 0.4
-	‘Left Arm’ 
o	Position:
	x = -0.35
	y = -0.15
	z = 0.25
	Rotation in x-axis = -7˚
	Rotation in y-axis = 70˚
	Rotation in z-axis = 9˚
o	Scaling:
	x = 0.57
	y = 0.3
	z = 0.4
-	‘Right Leg’ 
o	Position:
	x = 0.285
	y = -0.32
	z = -0.385
	Rotation in x-axis = 135˚
	Rotation in y-axis = -32˚
	Rotation in z-axis = -25˚
o	Scaling:
	x = 0.6
	y = 0.4
	z = 0.8
-	‘Left Leg’ 
o	Position:
	x = -0.285
	y = -0.32
	z = -0.385
	Rotation in x-axis = 135˚
	Rotation in y-axis = 32˚
	Rotation in z-axis = 25˚
o	Scaling:
	x = 0.6
	y = 0.4
	z = 0.8
Create a capsule game object for hat rim.  Rename the object to ‘Rim’.  Following are the scaling and position values:
-	Position:
o	x = 0
o	y = 0.1345
o	z = -0.0515
o	Rotation in x-axis = -21˚
-	Scaling:
o	x = 1
o	y = 0.1
o	z = 1
Next, create the beanie by creating a sphere game object.  Input the position and scaling values shown below:
-	Position:
o	x = 0
o	y = 0.15575
o	z = -0.0575
o	Rotation in x-axis = -80˚
-	Scaling:
o	x = 0.92		
o	y = 0.9867
o	z = 0.8218
Now, create the game object called ‘Pom Pom’ for the little ball above the beanie with the following position and scaling values.  
-	Position:
o	x = 0
o	y = 0.35
o	z = -0.58
-	Scaling:
o	x = 0.2		
o	y = 0.2
o	z = 0.2

For the last Kirby variant, take the Main Kirby prefab, drag it onto the scene and scale all values down to (0.25,0.25, 0.25).  Next, modify arm and leg position and scaling values to design a floating (jumping) Kirby.
-	‘Right Leg’ 
o	Position:
	x = 0.2
	y = -0.285
	z = -0.4
	Rotation in x-axis = 145˚
	Rotation in y-axis = -14˚
	Rotation in z-axis = -25˚
o	Scaling:
	x = 0.6
	y = 0.4
	z = 0.9
-	‘Left Leg’ 
o	Position:
	x = -0.2
	y = -0.285
	z = -0.4
	Rotation in x-axis = 145˚
	Rotation in y-axis = 14˚
	Rotation in z-axis = 25˚
o	Scaling:
	x = 0.6
	y = 0.4
	z = 0.9
-	‘Right Arm’ 
o	Position:
	x = 0.45
	y = -0.025
	z = 0.1
	Rotation in y-axis = 22˚
	Rotation in z-axis = -11˚
o	Scaling:
	x = 0.5
	y = 0.3
	z = 0.3
-	‘Left Arm’ 
o	Position:
	x = -0.45
	y = -0.025
	z = -0.1
	Rotation in y-axis = -22˚
	Rotation in z-axis = 11˚
o	Scaling:
	x = 0.5
	y = 0.3
	z = 0.3

