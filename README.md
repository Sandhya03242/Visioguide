# VisioGuide: Smart Cap for Object Detection and Navigation

VisioGuide is a smart cap designed to assist visually impaired individuals by providing real-time object detection and audio feedback about their surroundings. The system utilizes a Raspberry Pi 3, a USB webcam, and TensorFlow to detect objects and convey information through speech synthesis.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)

## Project Overview

VisioGuide aims to empower blind and visually impaired individuals by enabling them to recognize everyday objects (e.g., furniture, vehicles) and navigate their environment independently. The system captures images in real-time using a webcam, processes them with a Convolutional Neural Network (CNN), and announces the detected objects via text-to-speech.

## Features

- **Real-time Object Detection**: Detects objects in the user’s environment using a pre-trained CNN model.
- **Audio Feedback**: Provides speech output for detected objects via the Pyttsx3 Text-to-Speech synthesizer.
- **Portable Design**: Lightweight and compact hardware for easy transport and use in various settings.

## Hardware Requirements

- Raspberry Pi 3
- USB Webcam
- Headphones
- Power Bank (with sufficient capacity for your usage)

## Software Requirements

- Python (version X.X)
- OpenCV
- TensorFlow (lite version)
- Numpy
- Pyttsx3 (for Text-to-Speech)

## Installation

### Clone the Repository
```bash
git clone https://github.com/Sandhya03242/visio-guide.git
cd visio-guide
```
### Install Dependencies
```bash
pip install -r requirements.txt
```
### Run the Application
```bash
python main.py
```



