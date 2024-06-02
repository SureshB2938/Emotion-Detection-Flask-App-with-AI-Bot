# emotion-detection-flask

Real-Time Emotion Detection with Flask and DeepFace

Features
Real-time Video Streaming: Streams video from the webcam to the web application.

Emotion Detection: Uses DeepFace to analyze the dominant emotion of detected faces.

Toggle Emotion Detection: Allows the user to start and stop emotion detection via a button in the web interface.

Face Detection: Draws rectangles around detected faces and displays the detected emotion above each face.


*Requirements

1.Python 3.6+
2.Flask
3.OpenCV
4.DeepFace

installation
Clone the repository:


 git clone : https://github.com/SureshB2938/emotion-detection-flask.git

cd emotion-detection-flask

Create a virtual environment and activate it:


python -m venv myenv

# On Windows use

 myenv\Scripts\activate


Manually install the necessary packages:

pip install Flask

pip install opencv-python

pip install deepface


Run the Flask application:


python app.py

Note: Make sure to connect the internet

![mini3](https://github.com/SureshB2938/emotion-detection-flask/assets/169986337/15da74da-e49a-467a-98b0-18569c929759)


Open a web browser and go to http://127.0.0.1:5000 to access the application.

Use the interface to start and stop the emotion detection:

Start Detection: Click on the "Start Emotion Detection" button to begin analyzing emotions.

Stop Detection: Click on the "Stop Emotion Detection" button to stop analyzing emotions.

To shutdown the application and release the webcam, click on the "Shutdown" button.
