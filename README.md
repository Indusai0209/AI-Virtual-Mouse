# AI Virtual Mouse

This project implements a hand gesture recognition system using OpenCV, MediaPipe, and PyAutoGUI to control system operations such as mouse movements, scrolling, brightness, and volume control through hand gestures.

## Features
-   Hand Gesture Detection  : Recognizes gestures like fist, V-sign, pinching, etc.
-   Control System Actions  : Move the cursor, scroll, click, change brightness, and adjust volume based on recognized gestures.
-   Multi-Hand Support  : Detects both left and right hands, distinguishing between primary and secondary hands for different controls.

## Setup

### Prerequisites
Ensure that Python 3.7 or above is installed on your system. You can install the required libraries by following the instructions below.

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-link>
Install the required libraries:
bash
Copy code
pip install -r requirements.txt
Running the Gesture Controller
To run the gesture controller:

bash
Copy code
python gesture_controller.py
The gesture recognition will start using your system's camera. The following gestures are recognized:

Fist: Click and drag
V Gesture: Move the mouse
Pinch (Major/Minor): Adjust system volume, brightness, or scroll
Palm: No action
Exit
Press Enter to exit the application.

Libraries Used
OpenCV: For capturing and processing video frames.
MediaPipe: For hand gesture detection and tracking.
PyAutoGUI: For simulating mouse and keyboard actions.
Math, Enum, ctypes: Various Python utilities.
