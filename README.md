# Speech Recognition System

## Overview
This project is a simple web-based application that utilizes the SpeechRecognition library to convert audio files into text. Users can upload an audio file, and the system will process it to produce a text transcript.

## Features
- Upload audio files for transcription.
- Converts speech from audio files into text using Google Web Speech API.
- Displays the transcribed text on the web interface.

## Technologies Used
- Python
- Flask
- SpeechRecognition library
- HTML/CSS (Bootstrap for styling)

## Installation

1.Clone the repository:
   git clone https://github.com/yourusername/repositoryname.git
   
2.Navigate to the project directory:
cd repositoryname

3.Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate

4.Install the required packages:
pip install -r requirements.txt

5.Run the Flask application:
python app.py

6.Open your web browser and navigate to:
http://127.0.0.1:5000/

## Usage
<b>Upload an audio file using the form on the homepage.</b>
<b>Click the "Transcribe" button to generate the text transcript of the audio.</b>
<b>The transcribed text will be displayed below the upload form.</b>

