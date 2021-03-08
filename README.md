# EyeCompass 

Version 2021.02.05

The EyeCompass is a gaze control drawing system enabling free-eye drawing. It uses gaze point to navigate with the brush and draws basic lines on the canvas. Starting drawing and stopping drawing are activated by the dwell click in 0.8 second. When the brush is activated, a circular compass cursor appears. Smooth curves can be drawn by gazeing through the edge of the cursor. It is also easy to drawing staight lines. The directional needle is to indicate the brush direction. Several types of the compass can be selected. The spiral cursor is used to compensate the eye tracking error for drawing circle. The directional needle array is used to draw strainght lines in a certain direction precisely. 

The drawing commands can be Undo and Redo at the corners in the leftside. Can also be erased. The brush size can be set by the Brush Size option. The canvas can be zoomed in or zoomed out at the corner in the rightside. The grid on the canvas is an assistive guideline for orienting the eyes. It can be closed or opened by the Grid Off or Grid On option. 

In the left menu, the View option is to disable the cursor to draw on the brush. In this mode, the canvas can be nudged up, left, down, right, and allow the user to make observations. It can be switch back to the Draw option. 

To exit the system, please click on the button "Save/Exit", choose "Yes" to save your image in the Document folder. Click "No" to exit without saving the file. 

(1) Setting:

C:\Users\dsv\Desktop\EyeCompass0205\PixelProject_Data\StreamingAssets\thisJson

{"Width":1900,   Canvas size

"Height":1000,  Canvas size

"Lerper1":15,

"Lerper2":0.8,  Dwell time

"Lerper3":0.0111111}  Damping speed, recommend within 0.01 to 0.005.

(2) Exiting:

Click on the button "Save/Exit"

Yes: Save the image to the folder Document of the user. And exit.

No: Do not save the image and exit.
