# Real-Time Face Recognition System

## Overview

This module extends face detection by identifying known individuals using facial recognition techniques. The system compares facial features extracted from a live webcam feed with previously stored facial encodings and displays the recognized person's name.

The project demonstrates practical biometric identification using computer vision and machine learning.

---

## Features

* Real-time face recognition
* Webcam-based live identification
* Known person database support
* Unknown person detection
* Bounding box and name display

---

## Technologies Used

* Python
* OpenCV
* Face Recognition Library
* NumPy

---

## Dataset Structure

```text
dataset/
│
└── Niketh.jpg
```

The system generates facial encodings from stored images and compares them with live webcam frames.

---

## Working Principle

1. Load known face images.
2. Generate facial encodings.
3. Capture webcam frames.
4. Detect faces in the frame.
5. Generate encoding for detected face.
6. Compare with known encodings.
7. Display matching person's name.

---

## Recognition Pipeline

```text
Known Image
     ↓
Face Encoding
     ↓
Webcam Frame
     ↓
Face Detection
     ↓
Face Encoding
     ↓
Encoding Comparison
     ↓
Person Identification
```

---

## Output Example

```text
Name: Niketh
```

If no match is found:

```text
Name: Unknown
```

---

## Applications

* Smart Attendance Systems
* Access Control Systems
* Biometric Authentication
* Visitor Management
* Security and Surveillance

---

## Learning Outcomes

* Face Recognition Fundamentals
* Facial Feature Encoding
* Biometric Identification
* Real-Time Computer Vision
* Machine Learning Applications
