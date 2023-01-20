# Eyes can draw: A high-fidelity free-eye drawing method with unimodal gaze control
# EyeCompass
Please refer to the paper as follow: 
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

This is an executable file developed in Unity 3D and based on C#. It is only temporarily compatible with Tobii 4C and Tobii 5 on the Windows system. The project file will be released soon. 

The EyeCompass is a gaze control drawing system enabling free-eye drawing. In the project folder, click "PixelProject" to open the application. This system uses a gaze point to navigate with the brush and draws primary lines on the canvas. Starting drawing and stopping drawing are activated by the dwell click in a customized dwell time, for example, 1 second. When the brush is activated, a compass interface appears on the cursor. Smooth curves can be drawn by gazing through the edge of the cursor and moving along. It is also easy to draw straight lines with the compass interface. The directional needle can indicate the brush direction and control the angles of drawn lines. Several types of compass interfaces can be selected. The spiral cursor compensates for eye tracking errors when drawing circles. The directional needle array is used to precisely draw straight lines at a specific angle. 

The drawing commands can be "Undo" and "Redo" at the left side's corners. It can also conduct erase with "Eraser". The brush size can be set via the "Brush Size" option. The canvas can be zoomed in or zoomed out at the corner of the right side. The grid on the canvas is an assistive guideline for orienting the eyes. It can be closed or opened by the "Grid Off" or "Grid On" option. 

In the left menu, the "View / Draw" button can switch the canvas between the View and Draw modes. The View mode disables the cursor from drawing on the canvas. In the View mode, the canvas can be nudged left, up, right, and down. This mode allows the user to make observations and avoid involuntary drawing. The mode can be switched back to the Draw mode by clicking the button again. In the Draw mode, the brush can draw on the canvas.

To exit the system, please click on the button "Save/Exit". Choosing "Yes" to save your image in the Document folder or "No" to exit without saving the file. 

(1) Setting:

C:\Users\dsv\Desktop\EyeCompass0205\PixelProject_Data\StreamingAssets\thisJson

{"Width":1900,   Canvas size

"Height":1000,  Canvas size

"Lerper1":15,

"Lerper2":0.8,  Dwell time

"Lerper3":0.0111111}  Damping speed, recommended within 0.01 to 0.005.

(2) Exiting:

Click on the button "Save/Exit"

Yes: Save the image to the Document folder under the root of the User folder in the computer. And exit.

No: Do not save the image and exit.

Warming: When the system is opened, it defaults to full-screen mode and will block the toolbar. Either exit the full-screen mode by pressing the Win button or click the button "Save/Exit" on the menu to close the window. This case is a legacy issue from developing in Unity.
