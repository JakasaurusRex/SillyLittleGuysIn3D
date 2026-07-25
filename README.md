# Silly Little Guys - In 3D

Hello! In this workshop, you will learn how to use Blender 3D to create silly little guys as I call them or [low-poly animals similar to Sneepsnorp3D's art style](https://www.youtube.com/@sneepsnorp3d). I will then go into some fun applications for where we can use the animals and show how we can take our animals and create a keychain with our animals dancing around on them! To preface - I am a noob at 3D modeling techniques but I know the basics and I would love to share them! 

Heres a brief list of the contents we will cover! 
- Blender like the kitchen appliance - All about Blender
- Creating life - Learning to 3D Model
- Sillyfying- Texturing and Shading
- Put a little boogie in it - Animating your model

## Blender like the kitchen appliance  - All about Blender 🥤🍹🧊🌪️
<img width="287" height="297" alt="Screenshot 2026-07-21 at 6 17 17 PM" src="https://github.com/user-attachments/assets/39086ab4-6945-4895-9bad-b8e9b1ed84a2" />

Blender is a **free open-source** 3D modeling software! In recent years, its become widely adopted by professionals and offers comporab;le feature sets to enterprise modeling softwares! What makes Blender to great is the low barrier to entry and the ease of use - despite it being a modeling software! 

Outside of this workshop there are thousands of videos and tutorials online teaching how to create characters, animations and worlds in Blender, but we will be going over the very basics.

Some crazy things that have been made in Blender:
**Flow**
[![Flow Trailer](https://img.youtube.com/vi/82WW9dVbglI/maxresdefault.jpg)](https://www.youtube.com/watch?v=82WW9dVbglI)
[![Flow BTS](https://img.youtube.com/vi/_kK6qDsB89I/maxresdefault.jpg)](https://www.youtube.com/watch?v=_kK6qDsB89I)

**Effects in Across the Spiderverse**

<img width="640" height="360" alt="image" src="https://github.com/user-attachments/assets/8d339167-6568-47b4-be6c-2f52b4349ecf" />


Here are some things that I have created with Blender:

| BILAF | QuickSave | Capybaras | 
| ------------- |------------- | -------------|
| <video width="400" height="400" src="https://github.com/user-attachments/assets/047f0105-b533-4a37-ba19-60b46e632df1"/>  |<img width="794" height="446" alt="image" src="https://github.com/user-attachments/assets/a90c3141-8bd7-4746-81c1-f29a025f8a7d" /> | <img width="702" height="462" alt="Screenshot 2026-07-21 at 6 26 13 PM" src="https://github.com/user-attachments/assets/b0fd629d-5dbe-4f7a-ade0-682941481ba7" />|



### Downloading Blender
[You should be able to find the download link here!](https://www.blender.org/download/)

<img width="598" height="330" alt="Screenshot 2026-07-24 at 9 50 09 PM" src="https://github.com/user-attachments/assets/9f7185e1-b069-4f04-9d2d-581fb0b34b97" />

You should see this popup after you open the app! I don't normally change the settings! 
<img width="493" height="450" alt="Screenshot 2026-07-24 at 9 51 14 PM" src="https://github.com/user-attachments/assets/68c6ce9a-f0d3-43cf-b583-edd4e2d97580" />


## Creating Life 🌱 - Learning to 3D Model
Before we start creating, first we will learn how to get around the editor! By the way, if you ever feel like you are missing something or need to restart, you can always close and reopen Blender or create a new file! The Blender user interface is a little daunting but we will take it all one step at a time! 

### Lil Cube and the Viewport ⏹️🎥
When we open up a file, we are always greeting with a lil cube sitting in 3D space within our viewport! Get familiar with moving the view around the space, especially if you are unfamiliar with 3D environments! If you are using a track pad, you can use two fingers to rotate around and hold shift and 2 fingers to pan, pinch to zoom! Using a mouse, you can using the middle mouse button and shift + middle mouse button to rotate and pan and scroll to zoom!

In the top right corner, theres a variety of view settings. 

<img width="162" height="256" alt="Screenshot 2026-07-24 at 10 13 33 PM" src="https://github.com/user-attachments/assets/9e941de0-9e7d-4db6-80fc-2c19f81814cd" />

On the top of this group of settings we have a little gizmo that lets us instantly jump to different camera viewpoints, corresponding to the different axes, by clicking or you can hold it down to rotate the view. Below that there is a zoom button, a pan button, a button that makes the view show what the **camera** is capturing, and a button that switches you from a perspective view to orthogonal view! Another fast shortcut for changing the view quickly is holding the ```~``` key. Upon doing so, you will see a radial dial of different views you can pick. These are the same views accessible by clicking on the gizmo! 

<img width="544" height="405" alt="Screenshot 2026-07-24 at 10 18 42 PM" src="https://github.com/user-attachments/assets/1024f08b-8b88-4397-a9fe-18ddf6887521" />

Lets move to the left toolbar!

<img width="227" height="387" alt="Screenshot 2026-07-24 at 10 25 32 PM" src="https://github.com/user-attachments/assets/218696c6-bb05-4ecc-b794-1b54515a4e35" />

In the order listed:
- Select Tool
  - This is the basic tool that lets us select any object within the viewport!
- Cursor Tool
  - This tool lets us control the cursor.
  - You might notice the little crosshair in the center of the viewport, thats the cursor! Its the location objects are positioned when they are added to the scene.
  - You can open a cursor menu by holding ```Shift + S``` which provides a bunch more options related to the cursor, including resetting it to the origin (0, 0, 0)
- Move Tool
  - This tool lets us move selected objects around!
  - The arrows that appear near the object are draggable and let you move it around.
  - Alternatively, you can also move selected objects around by pressing the G key!
  - By pressing the ```G``` key you can also move objects by typing the amount of units to move them.
    - <img width="438" height="40" alt="Screenshot 2026-07-24 at 10 32 05 PM" src="https://github.com/user-attachments/assets/fc444e8f-d9ee-4c94-ad64-2a921c588e9e" />
    - At the top of your screen you should see this little popup. By typing, we can start filling out a vector that tells us how many units to move the object in each direction, X, Y, and Z!
    - You can press ```Tab``` to switch between which axis to edit, or you can move 1 axis at a time by pressing that axis (either the ```X```, ```Y``` or ```Z``` key) and then typing in the movement amount.
- Rotate Tool
  - The rotate tool works similar to the move tool, but instead we have a rotatey circle now!
  - Like the move tool, we can use the ```R``` key to rotate an object.
  - Also like the move tool, we can type out the amount we want to the entire obejct by or the amount on any of the axes.
- Scale Tool
  - The scale tool also behaves similarly to the other tools. Now we have pulley squares
  - The shortcut for the scale tool is the ```S``` key.
  - We can also type out the amount to scale the whole object or just 1 of the specific axes.
- Transform Tool
  - The transform tool lets us perform any of the previous 3 tools' transformations, all in 1 mode!
 
The rest of the tools in the toolbar are not as important, but feel free to mess around with them! 

At the bottom of the screen, is the timeline. We won't be messing around with the timeline until the end of the workshop! But we will cover it then!

On the right side of the screen, at the top is the outliner. It contains a list of all of the objects in the scene. There we can nest objects within each other, toggle their visibility and more by right clicking the objects! 

<img width="286" height="151" alt="Screenshot 2026-07-24 at 10 43 33 PM" src="https://github.com/user-attachments/assets/c91ae9dd-591f-46a0-91a0-697ae21b953d" />

Below that we have the properties panel. 

<img width="268" height="624" alt="Screenshot 2026-07-24 at 10 43 45 PM" src="https://github.com/user-attachments/assets/593222d6-1837-46e1-9352-56627b42f0dd" />

We won't go through everything, but the most important tabs for our beginner purposes are the **Objects, Modifiers, Data, and Materials** tabs! 

Finally, we will speedily talk about the top panel and tabs. 

<img width="1235" height="70" alt="Screenshot 2026-07-24 at 10 46 53 PM" src="https://github.com/user-attachments/assets/aabab76e-1217-4f94-aefd-a67a323b88b1" />

At the very top of the screen we have various different ways of viewing our scene. For our noob purposes, we are going to be mostly using Layout Mode - for organizing our objects, Modeling Mode - for designing and creating our objects, and UV Editing and Texture Paint - for painting our objects. 

Below that there are some more various menus related to our view, creating selections, adding new objects (which you can also do with the shortcut ```Shift + A```) and modifying the selected object! One cool tool in the center of the viewport header is the Proportional Editing mode, which proportionally applies edits to everything within the circle based on the distance from the center of the circle - this will become super useful later! On the right side of the header, there is some modes for how we visualize the scene, including viewport shading, which lets us see how things are colored! 

Last shortcut that might be useful is ```X``` to delete!

### Monkey Challenge 🐵🐵🐵 !
Using what we have learned so far, add a Monkey mesh (this should be in the list of available meshes) and apply some fun transformations to it! Try to see if you can find out how to change the color of the Monkey and we can share our Monkeys! 

Heres my Monkey: 

<img width="957" height="536" alt="Screenshot 2026-07-24 at 11 03 23 PM" src="https://github.com/user-attachments/assets/724e61fe-b25b-4a6b-9d6e-44b1d8aeeae9" />

This cheet sheet is honestly a little overwhelming but might be useful if you are stuck! 

<img width="350" height="500" alt="image" src="https://github.com/user-attachments/assets/016ba589-26d8-47ba-b2d9-7278a0b9ef5b" />

### Extrude to the moon 🌙 - Edit Mode

Now we are going to learn about edit mode! This is where the power of a 3D modeling software becomes aparent! 

Feel free to save your monkey, but lets go back to a blank slate with the cube!

With the cube selected, press ```Tab``` to enter **Edit Mode**. You should now see something like this! 

<img width="543" height="378" alt="Screenshot 2026-07-24 at 11 07 46 PM" src="https://github.com/user-attachments/assets/3cac2db5-5246-44fc-ba35-ea3ed75b5533" />

We can now click on the individual corners of the cube! Clicking on one and pressing ```G```, we can move our vertex around and change the shape of the cube! If you hold ```Shift```, you can select multiple vertices. By pressing ```1, 2``` or ```3```, you can switch between ```Vertex, Edge``` and ```Face``` selection respectively, which let us transform different parts of the object. 

With a face selected, I can apply multiple transformation steps like below where I moved the face using the move tool and then I rotated it! 

<img width="406" height="402" alt="Screenshot 2026-07-24 at 11 12 38 PM" src="https://github.com/user-attachments/assets/05d275f4-e6e4-4bd4-bb14-e58f39b3f382" />

With any face, edge or vertex of the cube selected, try pressing ```E``` to **Extrude**. This essentially duplicates the selection and adds it onto the geometry of the object. Now we can let our imaginations run wild! With extrusions I have exploded my cube into a prism kinda thing:

<img width="575" height="470" alt="Screenshot 2026-07-24 at 11 16 19 PM" src="https://github.com/user-attachments/assets/224c54e6-729a-485e-b7ea-e1c796f95ba5" />

Lets undo whatever changes you made! One last new tool is the Loop Cut tool. By pressing **Control + R** or selecting the tool from the left toolbar (in Edit Mode), we can hover over our object and place a loop along the different axes of it. This lets us subdivide our geometry into more points that we can use to manipulate it!

Another random note about Blender is that when using tools, creating objects or interacting with them, ocassionally there is a tooltip in the bottom left corner that can give you so more options! Keep an eye out for that as it might have some useful options, especially when creating an object! 
|  |
| ------------- |
| <video width="400" height="400" src="https://github.com/user-attachments/assets/ad5155fd-f954-43de-9bac-08f0630aec63"/>  | 

### Edit Mode Challenge

Take some time to explore the new tools we have available in Edit mode in the toolbar! Another useful tool to check out is the Rip Tool (```V```)! Try to mess around with them and see if you can make something cool! 


Heres a flower I made:

|  |
| ------------- |
| <video width="400" height="400" src="https://github.com/user-attachments/assets/ac5f1e07-6f85-4e59-a5a0-45bc9fc1778a"/>  | 















