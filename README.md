**README.md**

# Gestodrive

## Overview
Gestodrive is a Python-based application that utilizes computer vision and hand tracking to control a virtual driving interface. By detecting hand movements through a webcam, users can steer left or right and activate a nitro boost, simulating a driving experience without the need for physical controls.

## Features
- **Hand Tracking**: Utilizes MediaPipe to detect and track hand movements in real-time.
- **Steering Control**: Users can steer left or right based on the slope of their hands.
- **Nitro Activation**: Users can activate a nitro boost by raising their right hand.
- **Real-time Feedback**: Displays frames per second (FPS) and current actions on the screen.

## Technologies Used
- Python
- OpenCV (for video capture and image processing)
- MediaPipe (for hand tracking)
- Imutils (for image manipulation)
- Pynput (for keyboard control)

## Installation
1. Ensure you have Python installed on your machine.
2. Install the required packages:
   ```bash
   pip install opencv-python mediapipe imutils pynput
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Gestodrive.git
   ```
4. Navigate to the project directory:
   ```bash
   cd Gestodrive
   ```
5. Run the application:
   ```bash
   python gestodrive.py
   ```

## Usage
- Upon launching the application, the webcam will activate, and hand tracking will begin.
- Move your hands to steer left or right.
- Raise your right hand to activate the nitro boost.
- The application will display the current FPS and steering actions on the screen.

## Configuration
- **Nitro Key**: The key for activating nitro can be changed in the code (default is 'n').
- **Sensitivity**: Adjust the sensitivity of steering detection by modifying the `SENSITIVITY` constant in the code.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

