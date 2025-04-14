# Keyboard Typing with Eyes

A Python-based application that enables users to type using eye movements and blinking. This project uses computer vision and facial landmark detection to create an accessible typing interface controlled by eye gaze and blinks.

## Features

- **Eye-Controlled Keyboard**: Two keyboard layouts (left and right) that can be selected by looking at the respective side
- **Blink Detection**: Uses facial landmarks to detect eye blinks for character selection
- **Gaze Tracking**: Tracks eye movement to determine which key the user is looking at
- **Audio Feedback**: Provides audio cues for keyboard selection and character input
- **Visual Interface**: Clean and intuitive keyboard layout with visual feedback for selected keys

## Requirements

- Python 3.x
- OpenCV (cv2)
- dlib
- numpy
- pyglet
- shape_predictor_68_face_landmarks.dat (dlib's facial landmark predictor)

## Installation

1. Clone this repository
2. Install the required dependencies:
   ```bash
   pip install opencv-python numpy dlib pyglet
   ```
3. Download the facial landmark predictor file (shape_predictor_68_face_landmarks.dat) and place it in the project directory

## Usage

1. Run the main script:
   ```bash
   python Keyboard_Typing_with_Eyes.py
   ```
2. Position yourself in front of the camera
3. Look left or right to select the keyboard layout
4. Use eye gaze to select a key and blink to type the character
5. Press 'Esc' to exit the application

## Keyboard Layouts

### Left Keyboard
```
Q W E R T
A S D F G
Z X C V <
```

### Right Keyboard
```
Y U I O P
H J K L _
V B N M <
```

## Notes

- Ensure proper lighting for optimal eye tracking
- Keep your face within the camera's view
- The application requires a webcam for operation
- The '<' key functions as a backspace/delete key

## License

This project is open source and available under the MIT License.