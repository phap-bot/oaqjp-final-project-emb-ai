# Emotion Detection Application using Watson NLP

This project implements an AI-based emotion detection application using Python, Flask, and the IBM Watson NLP EmotionPredict library.

## Project Description
The Emotion Detection application analyzes input text and detects the emotion scores for:
- Anger
- Disgust
- Fear
- Joy
- Sadness

It also determines the **dominant emotion** from the evaluated text. A web user interface powered by Flask allows users to enter custom statements and receive real-time emotion detection results, along with comprehensive error handling for blank or invalid inputs.

## Project Structure
```
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── 6b_deployment_test.png
├── 7c_error_handling_interface.png
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/phap-bot/oaqjp-final-project-emb-ai.git
cd oaqjp-final-project-emb-ai
```

2. Install the required dependencies:
```bash
pip install flask requests pylint
```

3. Run the Unit Tests:
```bash
python -m unittest test_emotion_detection.py
```

4. Start the Flask Application:
```bash
python server.py
```
Access the application by navigating to `http://localhost:5000` in your browser.

5. Run Static Code Analysis:
```bash
pylint server.py
```
