# Final Project: Emotion Detection Application

## Project Name
**EmotionDetection** — An AI-based Emotion Detector using Watson NLP

## Description
This project is a web application that uses IBM Watson NLP to detect emotions in text.
It analyzes text input and returns scores for five emotions: anger, disgust, fear, joy, and sadness,
along with the dominant emotion.

## Project Structure

```
emotion_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Tasks Completed

- **Task 1**: Created the `emotion_detector` function using Watson NLP
- **Task 2**: Built the application and tested imports
- **Task 3**: Formatted the output of the emotion detector
- **Task 4**: Packaged the application as `EmotionDetection`
- **Task 5**: Unit tested the emotion detector for all 5 emotions
- **Task 6**: Deployed the application as a Flask web server
- **Task 7**: Added error handling for blank/invalid input
- **Task 8**: Ran static code analysis with pylint

## How to Run

```bash
python server.py
```

Visit `http://localhost:5000` in your browser.

## Technologies Used
- Python 3
- Flask
- IBM Watson NLP (Emotion Predict)
- unittest
- pylint
