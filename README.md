# Object Detection with YOLOv4-Tiny

## 📋 Overview
This project demonstrates how to perform real-time object detection using the YOLOv4-Tiny model. The code processes an image, detects objects specified by the user, and displays the annotated image in a resizable window.

---

## 🛠️ Features
- **YOLOv4-Tiny Integration**: Utilizes a lightweight yet powerful deep learning model for object detection.
- **Customizable Detection**: Allows users to specify which object categories to detect.
- **Real-time Visualization**: Highlights detected objects with bounding boxes and labels.
- **User-friendly Input**: Accepts image paths and object categories interactively.

---

## 📁 Project Structure
```plaintext
project/
│
├── resources/
│   ├── yolov4-tiny.cfg        # YOLOv4-Tiny configuration file
│   ├── yolov4-tiny.weights    # Pre-trained YOLOv4-Tiny weights
│   ├── coco.names.txt         # List of COCO dataset class names
│
├── main.py                    # Entry point for the project
```

## 🚀 Getting Started

### 1️⃣ Prerequisites
Ensure you have the following installed:

- Python 3.7+
- OpenCV
- NumPy

###2️⃣ Installation
Clone this repository:
```plaintext
git clone https://gitlab.com/your-repo/object-detection-yolov4-tiny.git
cd object-detection-yolov4-tiny
```
Install dependencies:
```plaintext
pip install -r requirements.txt
```

Download the YOLOv4-Tiny weights and configuration files if not already included.

