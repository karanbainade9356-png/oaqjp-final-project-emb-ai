# Emotion Detector - Final Project

## Project Overview
This is an **AI-based Emotion Detection** web application built using **Python**, **Flask**, and the **Watson NLP Library**. The application analyzes user-provided text and detects emotions such as **anger**, **disgust**, **fear**, **joy**, and **sadness**, returning the dominant emotion.

## Features
- Emotion detection using Watson NLP Embedded AI
- Web interface for text input and emotion analysis
- Error handling for blank/invalid inputs
- Unit tested with full test coverage
- PEP 8 compliant (pylint 10/10 score)

## Project Structure
```
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
├── requirements.txt
└── README.md
```

## Technologies Used
- Python 3.x
- Flask
- Watson NLP Library
- HTML / Bootstrap / JavaScript

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the server: `python server.py`
3. Open `http://localhost:5000` in your browser

## License
Apache License 2.0
