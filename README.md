Face Detection with OpenCV and Dlib
Description
This project demonstrates real-time face detection using OpenCV and Dlib libraries in Python. The application captures video from your computer's default camera, detects faces, and displays the results with bounding boxes and face numbers.

Features
Real-time face detection
Displays detected faces with bounding boxes
Shows face numbers above each detected face
Requirements
Python 3.x
OpenCV
Dlib
NumPy
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/opencv-face-detection.git
Navigate to the project directory:
bash
Copy code
cd opencv-face-detection
Install the required packages:
bash
Copy code
pip install opencv-python dlib numpy
Usage
Run the script:
bash
Copy code
python face_detection.py
Press q to exit the application.
Code Explanation
The code captures video from the webcam, converts each frame to grayscale, and detects faces using Dlib's frontal face detector. Detected faces are marked with rectangles, and a counter displays the number of faces detected.

Key Functions:
cv2.VideoCapture(0): Connects to the default camera.
dlib.get_frontal_face_detector(): Initializes the face detector.
cv2.rectangle(): Draws rectangles around detected faces.
cv2.putText(): Annotates the detected faces with a number.
Example Output
<!-- Add a path to a screenshot or example output image -->

Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

License
This project is licensed under the MIT License.
