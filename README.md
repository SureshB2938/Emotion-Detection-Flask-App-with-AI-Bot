Emotion-Detection-Flask-App-with-AI-Bot

Real-Time Emotion Detection with Flask, DeepFace, TensorFlow/Keras, and AI Bot

Features
Real-time Video Streaming: Streams video from the webcam to the web application.

Emotion Detection: Uses DeepFace to analyze the dominant emotion of detected faces.

Toggle Emotion Detection: Allows the user to start and stop emotion detection via a button in the web interface.

Face Detection: Draws rectangles around detected faces and displays the detected emotion above each face.

AI Chat Bot: Integrated AI bot available on the home page for interactive assistance, built using Azure.

Requirements

Python 3.6+

Flask

OpenCV

DeepFace

TensorFlow

Keras

Installation

Clone the repository:

command prompt

git clone https://github.com/SureshB2938/Emotion-Detection-Flask-App-with-AI-Bot.git

cd Emotion-Detection-Flask-App-with-AI-Bot

Create a virtual environment and activate it:

command prompt

python -m venv myenv

# On Windows use

myenv\Scripts\activate

# On macOS/Linux use

source myenv/bin/activate

Manually install the necessary packages:

command prompt 

pip install Flask

pip install opencv-python

pip install deepface

pip install tensorflow

pip install keras

Run the Flask application:

python app.py

Note: Make sure to connect to the internet.

Open a web browser and go to http://127.0.0.1:5000 to access the application.

Use the interface to start and stop the emotion detection:

Start Detection: Click on the "Start Emotion Detection" button to begin analyzing emotions.

Stop Detection: Click on the "Stop Emotion Detection" button to stop analyzing emotions.

Shutdown: To shutdown the application and release the webcam, click on the "Shutdown" button.


Use the AI Chat Bot:

On the home page, interact with the AI bot to get details about the project. Simply type in your questions related to the project, and the bot will provide the necessary information.
