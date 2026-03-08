🚨 AI Motion Detection Security Alarm

A lightweight Python security application that uses computer vision to detect movement and trigger an audible alarm.

🌟 How it Works

The script uses a technique called Frame Differencing:

It captures two frames in rapid succession.

It calculates the absolute difference between them using cv2.absdiff.

It converts the difference to Grayscale and applies a Threshold to highlight movement.

If the area of movement (contour) is larger than 5000 pixels, it triggers a winsound.Beep.

🛠️ Prerequisites

Windows OS (required for the winsound library).

Python 3.x

OpenCV library.
