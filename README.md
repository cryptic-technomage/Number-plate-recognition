# Number Plate Recognition using OpenCV

This project demonstrates the detection of vehicle number plates in both images and videos using Haar Cascade Classifiers with OpenCV. Detected plates are highlighted with bounding boxes, labeled appropriately, and blurred to preserve privacy.

---

## Introduction

Automatic Number Plate Recognition (ANPR) is an intelligent video analysis technology that detects and reads vehicle registration plates in real time. It plays a critical role in traffic enforcement, smart parking systems, toll collection, and surveillance.

In this project, we leverage OpenCV and pre-trained Haar Cascade classifiers to create a lightweight and efficient solution for number plate detection in both images and video streams.

---

## Project Overview

This system has two main capabilities:

- *Image-Based Plate Detection*: Accepts a static image, detects vehicle number plates, applies a blur effect for anonymization, and displays the processed image.
  
- *Video-Based Plate Detection*: Accepts a video file, detects number plates frame-by-frame in real-time, marks them with bounding boxes, and applies a blur effect.

*Key Features:*
- Lightweight and easy to use
- Fast detection using Haar Cascades
- Supports images (.jpg, .png) and video files (.mp4, etc.)
- Privacy-focused with automatic blurring of detected plates

---

## Tech Stack

- *Programming Language:* Python 3.x  
- *Libraries Used:*
  - OpenCV – for image/video processing and detection
  - NumPy – for efficient array manipulation

---

## Project Usage

This project can be effectively used in various real-world applications:

- *Smart City Traffic Monitoring:* Helps monitor and anonymize license plates in public video feeds.
- *Automated Toll Booths:* Forms the detection foundation for capturing vehicle data.
- *Surveillance Systems:* Can be embedded into surveillance solutions to track and record vehicle presence while ensuring privacy.
- *Dataset Preparation:* Ideal for preprocessing datasets by blurring identifiable number plates before training or publishing.

---

## How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/cryptic-technomage/number-plate-recognition.git
cd number-plate-recognition


## Conclusion

This project provides a practical and efficient solution for detecting and anonymizing vehicle number plates using OpenCV and Haar Cascade Classifiers. It demonstrates the core concepts of image and video processing, object detection, and real-time application development. While the current implementation effectively detects and blurs license plates, it can be further enhanced by integrating Optical Character Recognition (OCR) tools like Tesseract for reading plate numbers, or deep learning models for improved accuracy and robustness.

This system serves as a foundational tool for developers and researchers working on intelligent transportation systems, surveillance, and smart city applications.
