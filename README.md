🎮 Hand Gesture Control System

Control your system's volume and media playback using just your hand gestures! This project combines computer vision, machine learning, and system automation to create an interactive and fun experience.

✨ Features

Volume Control: Adjust your system's volume by moving your thumb and index finger closer or farther apart.

Play/Pause Media: Perform a pinch gesture (thumb and index finger touching) to toggle play/pause on your media player.

🗂 How It Works

Hand Detection: Uses the MediaPipe Hands model to detect and track hand landmarks in real time.

Gesture Recognition: Measures the distance between key points on the hand (thumb and index finger) to determine the gesture.

Volume Mapping: Maps the finger distance to the system's volume range using PyCaw.

Media Control: Uses PyAutoGUI to simulate key presses for play/pause functionality.

🛠 Tech Stack

Python

OpenCV

MediaPipe Hands

PyCaw

PyAutoGUI

🚀 Getting Started

Prerequisites

Install Python 3.9

Install the required libraries:

pip install opencv-python mediapipe numpy pycaw pyautogui comtypes

Running the Project

Clone this repository:

git clone https://github.com/yourusername/hand-gesture-control.git
cd hand-gesture-control

Run the script:

python hand_gesture_control.py

Use your webcam to control the system!

🎯 Future Improvements

Add gestures for skipping tracks, brightness control, and more.

Enhance gesture recognition accuracy for better user experience.

📸 Demo

Here’s a quick look at the project in action:

https://www.linkedin.com/in/harsh-vardhan-06a291298/

🧪 Contributing

Feel free to fork this repository, submit issues, or create pull requests for improvements!

📧 Contact

For any questions, reach out at  Theharshvardhan2@gmail.com or connect with me on https://www.linkedin.com/in/harsh-vardhan-06a291298/.
