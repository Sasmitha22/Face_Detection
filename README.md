# Real-Time Face Detection using OpenCV

This Python script utilizes OpenCV to perform real-time face detection using the Haar cascade classifier. It captures video from the default webcam and detects faces in the video feed, drawing rectangles around detected faces.

## Requirements
- Python
- OpenCV (cv2)

## Installation
1. Make sure you have Python installed on your system.
2. Install OpenCV using pip:
   ```
   pip install opencv-python
   ```
3. Download the `haarcascade_frontalface_default.xml` file from OpenCV's GitHub repository or any other reliable source.

## Usage
1. Clone this repository or download the script (`face_detection.py`) to your local machine.
2. Place the `haarcascade_frontalface_default.xml` file in the same directory as the script.
3. Run the script by executing the following command:
   ```
   python face_detection.py
   ```
4. The script will open a window showing the webcam feed with detected faces highlighted by rectangles.
5. Press 'q' to exit the program.

## Parameters
- `alg`: Path to the Haar cascade classifier XML file. By default, it uses `haarcascade_frontalface_default.xml`.
- `cam`: VideoCapture object, capturing video from the default webcam (index 0). Change the index if using a different camera.

## Modification
- You can modify the `alg` variable to use a different Haar cascade classifier file for detecting other objects (e.g., eyes, smile).
- Adjust the parameters passed to `detectMultiScale` for better face detection performance based on your requirements.

## Contribution
Contributions are welcome! Feel free to fork this repository, make changes, and submit pull requests.

```
