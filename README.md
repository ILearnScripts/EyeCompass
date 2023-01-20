# EyeCompass 
Please refer to the paper: 
#Eyes can draw: A high-fidelity free-eye drawing method with unimodal gaze control
Huang L, Westin T, Eladhari M P, et al. Eyes can draw: A high-fidelity free-eye drawing method with unimodal gaze control[J]. International Journal of Human-Computer Studies, 2023, 170: 102966.

@article{huang2023eyes,
  title={Eyes can draw: A high-fidelity free-eye drawing method with unimodal gaze control},
  author={Huang, Lida and Westin, Thomas and Eladhari, Mirjam Palosaari and Magn{\'u}sson, Sindri and Chen, Hao},
  journal={International Journal of Human-Computer Studies},
  volume={170},
  pages={102966},
  year={2023},
  publisher={Elsevier}
}

Version 2021.02.05 (Introduction video: https://youtu.be/FSMlCnPB27k)

The EyeCompass is a gaze control drawing system enabling free-eye drawing. In the project folder, clicking the "PixelProject" to open the application. This system uses gaze point to navigate with the brush and draws basic lines on the canvas. Starting drawing and stopping drawing are activated by the dwell click in a customized dwell time, for example, 1 second. When the brush is activated, a compass interface appears on the cursor. Smooth curves can be drawn by gazing through the edge of the cursor and moving along. It is also easy to draw straight lines with the compass interface. The directional needle can indicate the brush direction and control the angles of drawn lines. Several types of the compass interfaces can be selected. The spiral cursor is used to compensate with eye tracking errors when drawing circle. The directional needle array is used to draw strainght lines in a certain direction precisely. 

The drawing commands can be Undo and Redo at the corners of the leftside. It can also conduct erase with Eraser. The brush size can be set by the Brush Size option. The canvas can be zoomed in or zoomed out at the corner of the rightside. The grid on the canvas is an assistive guideline for orienting the eyes. It can be closed or opened by the Grid Off or Grid On option. 

In the left menu, the View option is to disable the cursor to draw on the canvas. In this mode, the canvas can be nudged left, up, right, and down. This mode allows the user to make observations and avoid involuntary drawing. It can be switched back to the Draw mode by the Draw option. 

To exit the system, please click on the button "Save/Exit". Choosing "Yes" to save your image in the Document folder, or "No" to exit without saving the file. 

(1) Setting:

C:\Users\dsv\Desktop\EyeCompass0205\PixelProject_Data\StreamingAssets\thisJson

{"Width":1900,   Canvas size

"Height":1000,  Canvas size

"Lerper1":15,

"Lerper2":0.8,  Dwell time

"Lerper3":0.0111111}  Damping speed, recommend within 0.01 to 0.005.

(2) Exiting:

Click on the button "Save/Exit"

Yes: Save the image to the Document folder under the root of the User folder in the computer. And exit.

No: Do not save the image and exit.


