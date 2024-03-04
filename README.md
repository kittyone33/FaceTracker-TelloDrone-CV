# FaceTracker-TelloDrone-CV
This is a ComputerVision/Control algorithm which guides a DJI Tello drone to adjust the camera according to your face position.

# Dependencies 
This algorithm includes : <br>
djitellopy ver 1.5
opencv-python ver 4.1.0.25

Install the dependencies with: <br>
bash: <b> pip3 install -r requirements.txt </b>
# Usage

Start it using : <br>
bash: <b> python3 FaceDetection.py haarcascade_frontalface_default.xml </b>

# Videos
All test videos can be found on my youtube channel and I'll list them here: 
- First test, no PID, no face logging : https://www.youtube.com/watch?v=WFz5I1iRhLY

# Limitations

There are some current limitations, such as slow movements, set-point oscill