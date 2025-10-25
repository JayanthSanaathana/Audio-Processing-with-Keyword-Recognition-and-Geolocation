# Audio-Processing-with-Keyword-Recognition-and-Geolocation
This project allows users to detect specific keywords from spoken audio input and retrieve the current location using Google Maps API. It demonstrates how to use Python for speech recognition, keyword detection, and geolocation.

# Features

Audio Recognition: Recognizes spoken words using a microphone.
Keyword Detection: Checks for specific keywords (e.g., "emergency" and "help") in the audio input.
Timestamp Logging: Logs a timestamp each time a phrase is recognized.
Location Retrieval: Uses Google Maps API to fetch and display the location when keywords are detected.

# Requirements

To run this code, you need the following Python libraries:
SpeechRecognition: For capturing and transcribing audio input.
keyboard: To control the start and stop of recording with key presses.
gmaps: For Google Maps API integration.
requests: To make HTTP requests to Google Maps API.

# Installation

Install the required packages by running: pip install SpeechRecognition keyboard requests gmaps

Install PyAudio for audio input (especially on Windows):

pip install pyaudio

Add your Google Maps API Key in the code:

gmaps_key = "YOUR_GOOGLE_MAPS_API_KEY"

# Usage

To start the program: Run the script in your terminal or VS Code:
Follow the on-screen prompts:

Press "1" to begin recording your audio.
Speak into the microphone.
Press "0" to stop recording.
If a recognized phrase contains the keywords "emergency" or "help," the program will log a warning, add a timestamp, and retrieve your location using the Google Maps API.

#Code Overview
<img width="1156" height="437" alt="384334285-020119c3-1b94-4e20-a732-03d1ff2b4ef3" src="https://github.com/user-attachments/assets/fb0cd70b-95d8-43ee-bfa1-1c7c089f6010" />

