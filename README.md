Picture-Viewer
=================
Picture Viewer needs an opengl capable video card.

If you want to test the application, you can run Picture-Viewer.jar. Make sure that the "pictures" and "resources" folder is in the same place with the Picture-Viewer.jar. For the moment it only supports 6 pictures.

How to use in eclipse:
Before you can use this project in eclipse you should go to 'Project'->'Properties'->'Java Build Path'->'Libraries'. Unfold "lwjgl.jar" and set the "Native library location" to "lib/native-win" from the repo. You may want to use Jarsplice to create a jar of your own.

How to guide:
-pres LEFT or RIGHT arrow key to move through pictures
-click on the image
-press 'L' to use the magnification glass
-press the UP or DOWN arrow key to zoom in or zoom out in the magnification glass
-press 'B' to turn the picture's colors into black-and-white
-press 'C' to turn the picture's colors into color
-press 'S' to turn the picture's colors into sepia
-press 'D' to get information of the picture (only on windows)
