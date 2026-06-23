# Sign Language to Text and Speech Conversion

## Overview

Sign Language to Text and Speech Conversion is an AI-powered computer vision application that translates hand gestures into text and speech in real time. The project aims to bridge communication gaps between individuals who use sign language and those who do not understand it.

Using MediaPipe for hand landmark detection, OpenCV for image processing, and Deep Learning for gesture recognition, the system accurately identifies sign language gestures and converts them into readable text and audible speech.

---

## Features

* Real-time sign language recognition
* Hand landmark detection using MediaPipe
* Deep learning-based gesture classification
* Text generation from recognized gestures
* Text-to-speech conversion
* User-friendly interface
* High accuracy gesture prediction
* Efficient and responsive performance

---

## Technologies Used

* Python
* OpenCV
* MediaPipe
* TensorFlow / Keras
* NumPy
* Pyttsx3
* Machine Learning
* Deep Learning

---

## System Architecture

1. Capture live video through webcam.
2. Detect hand landmarks using MediaPipe.
3. Extract hand feature coordinates.
4. Process features using a trained deep learning model.
5. Predict the corresponding sign language gesture.
6. Convert the prediction into text.
7. Generate speech output from the recognized text.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Nunna-Sujatha/Sign-Language-To-Text-and-Speech-Conversion.git
cd Sign-Language-To-Text-and-Speech-Conversion
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

Run the application:

```bash
python final_pred.py
```

Show hand gestures in front of the webcam and the system will recognize them and convert them into text and speech output.

---

## Project Objectives

* Facilitate communication for individuals using sign language.
* Develop an accurate gesture recognition system.
* Convert sign language gestures into meaningful text.
* Generate speech output for recognized signs.
* Improve accessibility through artificial intelligence.

---

## Future Enhancements

* Support complete words and sentences.
* Recognize dynamic sign language gestures.
* Multi-language speech output.
* Mobile application deployment.
* Cloud-based real-time communication platform.

---

## Results

The system successfully recognizes sign language gestures in real time and converts them into text and speech with high accuracy, making communication more accessible and efficient.

---

