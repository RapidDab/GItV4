### Step 1
* First we open Unity Hub and make a new project. Now how do we do that, first find the  windows logo on your screen, click on it and search for "Unity Hub". Once you see it, click on it it will lead you to a page that looks something like this![[Pasted image 20240201214150.png]]
### Step 2
* Next click on "New Project" on the top right. Once there you will name your project and select the type of project we want to make. By default "3D" project will be selected but make sure that is selected with a blue square around it. For the name of our project you can name it anything you want but for our case lets call it "BombDrop". Finally unselcted the "Connect to Unity Cloud" option(you may need to scroll down on the right to find it). 
* Finally we can then Create the project and start building our game ![[Pasted image 20240201215419.png]]
### Step 3
* Once you are in Unity after it is done loading, it should look something like this with maybe a few things switched around ![[Pasted image 20240201215617.png]]
### Step 4
* Before we do all the cool game development stuff, there is a little set up we have to do. In the Hierarchy section to the left of your screen, right click the "Main Camera" game object and click "Delete" ![[Pasted image 20240201220216.png]]
### Step 5 
* Next lets add new camera by right clicking on the empty space in the Hierachy and add a camera. In the Inspector section on the right of your screen you should change the tag of the object to be a "MainCamera" . Like showed below                                             ![[Pasted image 20240201220722.png]]
* Now lets change some settings in the camera. First change the "Projection" to be Orthographic   There will now be a new setting called "Size" make sure that is set to 5![[Pasted image 20240201220921.png]]
### Step 6
* Now double click the 2D square on the left of the Scene View ![[Pasted image 20240201221403.png]]
### Step 7
* Now lets add some stuff to our scene. Lets add a cube just like how we added a Camera in step 4. Instead of going to Camera we will go to "3D Objects" once you click that you will get a drop down menu. There you will select a cube to add to you scene.![[Pasted image 20240201221901.png]]
### Step 8
* Now lets go back to the Inspector section of you screen. There you will see a small section that says "Transform" that is whats called a component of a game object and it is what is controlling the positon of the Cube in your scene. You can edit the values of x, y and z but make sure you Reset the positon by clicking the three dots and selecting "Reset"
* After that little side track lets add some Physics to our game object by going down to the bottom of your scene and click "Add Component". A menu should pop out, there you can search for "Rigidbody" and clicking it will add it to your scene. ![[Pasted image 20240201222753.png]]
### Step 9 
* We would want to bring up the Rigidbody component to take priority before the Box Collider(which was added by default) to do this we click the three dots and there should be a drop down menu, one of the options being "Move Up". ![[Pasted image 20240201223628.png]]
### Step 10 
* Next we would want to change the settings of the Rigidbody. We don't want to have it have any gravity nor do we want any other game object affecting it physics. We also don't want the cube to spin abnormally. To do this change your setting to look like the image below (Click where it says Constraints to show Freeze Rotation options)![[Pasted image 20240201224023.png]]
