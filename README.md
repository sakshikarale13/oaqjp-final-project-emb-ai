# Repository for final projec
# Emotion Detector Application

## Project Overview
This project implements an Emotion Detector application using the Watson Natural Language Processing (NLP) library. It analyzes text and identifies emotions expressed in the input.

## Objectives
- Analyze user-provided text.
- Identify anger, disgust, fear, joy, and sadness.
- Determine the dominant emotion.
- Display structured emotion detection results.

## Technologies Used
- Python
- IBM Watson NLP Emotion Prediction service
- Requests library
- Flask (for web deployment)
- HTML and CSS (for the user interface)

## Project Features
- Text-based emotion detection.
- Emotion score analysis.
- Dominant emotion identification.
- Web-based interface using Flask.
- Input validation and error handling.

## Project Structure
- `EmotionDetection/emotion_detection.py` — Emotion detection function.
- `server.py` — Flask web application.
- `test_emotion_detection.py` — Unit tests.

## How to Run
Install the required packages:

```bash
python -m pip install requests flask pylint
```

Run the application after configuring and verifying access to the Watson NLP service.

## Author
Sakshi Karale
