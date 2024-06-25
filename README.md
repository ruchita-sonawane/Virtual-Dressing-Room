# Virtual Dressing Room
The Virtual Dressing Room project is a Python application that uses computer vision and pose detection to overlay virtual shirts on a live webcam feed in real-time. Leveraging OpenCV and cvzone's PoseDetector, it accurately positions shirts based on body landmarks and allows users to switch shirts with gestures, offering an amazing experience.

Key Features:<br>
  Real-Time Webcam Feed: Captures live video from the webcam and displays it.
  Pose Detection: Uses the PoseDetector module from cvzone to detect the user's body pose in real-time.
  Shirt Overlay: Dynamically overlays a virtual shirt on the user's body based on detected landmarks.
  Shirt Selection: Allows the user to switch between different shirts using gesture controls.
  Resolution Adjustment: Sets the webcam feed resolution to 1280x720 for better clarity.

Implementation Details:
  Video Capture: The webcam feed is captured using OpenCV's VideoCapture.
  Pose Detection: The PoseDetector from cvzone is used to find the user's pose and landmarks.
  Shirt Overlay: The selected shirt image is resized and overlaid on the user's body based on shoulder landmarks.
  Gesture Control: Simple gesture controls (raising hands) are used to switch between different shirts.
  Image Processing: Shirts and button images are read and processed using OpenCV functions.

File Structure:
  main.py: The main script containing the implementation of the virtual dressing room.
  Resources/Shirts: A folder containing different shirt images to be overlaid.
  Resources/button.png: An image for the button used in the interface.

Requirements:
  Python 3.x
  OpenCV
  cvzone

Running the Project:
  Ensure you have all the required libraries installed.
  Place your shirt images in the Resources/Shirts folder.
  Run the main.py script to start the virtual dressing room.Running the Project:
  Ensure you have all the required libraries installed.
  Place your shirt images in the Resources/Shirts folder.
  Run the main.py script to start the virtual dressing room.

This project provides a fun and interactive way to try on different shirts virtually and can be extended to include more clothing items or additional features like saving snapshots, sharing on social media, etc.

Feel free to explore and modify the project to suit your needs!
