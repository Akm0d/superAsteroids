# superAsteroids
BYU CS 240 Super Asteroids Game mods

To add these to your super asteroids game:
 1. download the superAsteroids folder as a ZIP file
 2. unzip your download to your favorite location
 3. copy the contents of the "parts" folder to [path-to-asteroids-game]/SuperAsteroids/app/src/main/assets/images/parts/
 4. copy the "tylers_game.json" file to [path-to-asteroids-game]/SuperAsteroids/app/src/main/assets/
 
You are free to add more ships and modify the JSON file.  If you liked this then please contribute.
It takes about 30 minutes to make a new ship using gimp(windows,linux,and mac photo editing software).

To add a new ship you have to find a picture that you want to use, and open it in gimp.
First thing, click "image/scale" and set the height to about 900, the width will change to match the new height
This will scale your new image so it matches the height of all other ships in the database.

Use the select tool to cut out the different ship parts. 
once you have an entire part selected you can press "CTRL + X" and then go to "edit/paste as/paste as new image"
This way, your selection will become a new image with no background
Next go to "image/autocrop" to remove extra space

After you have all the parts separated with backgrounds removed go to "file/export as" and choose "png" as the file format
save each part to the "[path-to-asteroids-game]/SuperAsteroids/app/src/main/assets/images/parts/" folder
I named things by ship name first, and then part name: I.E.  falcon_mainBody.png, falcon_extraPart.png etc.

Finding the right attachpoints can be tricky.  There are several ways to do it.
 - before you split up an original image you can mark 2 pixels in a unique color and use those as references for attach points
 - You can guess and check, hold your cursor over what is close to the attach point and compile your app and then
  modify the numbers until it looks right

Make sure to edit the JSON file and add all the necessary attributes for each part.  
You can fork from my JSON file or make your own from scratch.
I will accept all of these if you push them back so that we can share with future students.

Tyler Johnson
