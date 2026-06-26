# Virtual-Paint-main

## Virtual Paint using OpenCV and Computer Vision

### Overview

Virtual Paint is a Python-based computer vision application that allows users to draw on a virtual canvas using a colored object instead of a mouse. The system captures live video through a webcam, detects the colored object using OpenCV, and tracks its movement to create drawings in real time.

### Features

* Real-time object tracking
* Virtual drawing using a colored marker
* Multiple color selection
* Eraser and clear canvas options
* Simple and interactive user interface

### Technologies Used

* Python
* OpenCV
* NumPy

### Requirements

* Python 3.x
* OpenCV
* NumPy
* Webcam

### Installation

```bash
pip install opencv-python numpy
```

### Run the Project

```bash
python main.py
```

### Working

The webcam captures live video, converts each frame to the HSV color space, detects the selected colored object, tracks its movement, and draws continuous lines on a virtual canvas based on the object's position.

### Applications

* Digital Drawing
* Interactive Learning
* Gesture-Based Human-Computer Interaction
* Computer Vision Projects

### Future Enhancements

* Hand gesture recognition without colored markers
* Brush size adjustment
* Undo/Redo functionality
* Save drawings as images
