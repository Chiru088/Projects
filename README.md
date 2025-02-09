# Hand Distance Measurement using OpenCV and MediaPipe

This project measures the distance between fingertips of a detected hand using OpenCV and MediaPipe. The distance is displayed in centimeters on the screen.

## Features
- Detects hand using MediaPipe
- Draws landmarks and connections on the detected hand
- Calculates distances between fingertips
- Displays measured distances in real-time

## Requirements
Ensure you have Python installed and install the following dependencies:
```sh
pip install opencv-python mediapipe
```

## Usage
Run the script using:
```sh
python hand_distance.py
```

### Key Controls
- Press `q` to exit the application

## How It Works
1. Captures video from the webcam.
2. Uses MediaPipe to detect hand landmarks.
3. Identifies the coordinates of fingertips.
4. Calculates Euclidean distances between each pair of fingertips.
5. Converts pixel distances to centimeters using a predefined conversion factor.
6. Displays the measured distances on the screen.

## Customization
- Modify the `pixels_per_cm` value for more accurate real-world measurements.
- Adjust the landmark indices to measure different hand distances.

## License
This project is open-source and free to use.

