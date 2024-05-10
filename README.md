# Object Detection with Speech Feedback
This project uses OpenCV and cvlib for real-time object detection in a video stream, Google Text-to-Speech (gTTS) to convert detected object names into speech, and playsound to play the generated speech.

### Dependencies
* OpenCV
* cvlib
* gTTS
* playsound

You can install all these dependencies with pip

### How to Run
* Clone this repository.
* Navigate to the project directory in your terminal.
* Run python main.py.
* The script will start a video stream (using the first camera it finds). It will detect objects in the video stream and draw bounding boxes around them. When it detects a new object, it will say the name of the object out loud.

* Press the space bar to stop the script.

### Note
This script uses the camera index 1 in cv2.VideoCapture(1). If you have multiple cameras or if the script can't access your camera, you might need to change this index.

