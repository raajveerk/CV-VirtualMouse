# Virtual Mouse - CV Project

Hi, everyone.
This is a project that I made using opencv-python library and the mediapipe engine. I also made use of autopy GUI animation library for python.
The code editor of choice was PyCharm by JetBrains and I was running Python 3.8 as the interpreter.


This is an extension of the Flappy Bird Game that I made using pygame, earlier.
The idea was to play the game with hand gestures instead of mice/trackpad hardware.

You can find the repository for the game here:
https://github.com/raajveerk/FlappyBird_PyGame


## Setup:

--> To run the project, I'd suggest first create a virtual environment by running:

```commandline
    python -m venv myenv
```

--> Then, download the files into the same folder and open up PyCharm.

--> In PyCharm, go to settings:
"Ctrl+Alt+S"

--> Now go to the Python Interpreter Settings and choose the interpreter that is set for the Virtual Environment.
![alt text][]

--> Next, click the "+" button on the library window to install the following libraries:

1) opencv-python
![alt  text][]
2) mediapipe
![alt  text][]
3) autopy
![alt  text][]

--> After successfully installing these libraries, locate the AIVirtualMouse file and run it. It should open up your laptop's camera and track your hands successfully.

### Moving the Mouse:

To move the cursor of the mouse, have your index finger up and all the other fingers closed into a fist.

Similarly, to left-click on the screen, bring your middle and index finger closer.