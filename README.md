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


## 🚀 Getting Started

### 1️⃣ Prerequisites
Ensure you have the following installed:
- Python 3.7+
- OpenCV
- NumPy

### 2️⃣ Installation
Clone this repository:
```bash
git clone https://gitlab.com/your-repo/object-detection-yolov4-tiny.git
cd object-detection-yolov4-tiny
Install dependencies:

bash
Копировать код
pip install -r requirements.txt
Download the YOLOv4-Tiny weights and configuration files if not already included.

🖼️ Usage
Run the script:

bash
Копировать код
python main.py
Provide inputs:
Image Path: Enter the path to the image you want to process.
Objects to Detect: List the objects (e.g., car, person) or leave blank to detect all objects.
View Results:
The processed image with detected objects will be displayed in a resizable window.

🔧 Key Functions
draw_text

Adds text labels with an outline to the image.
object_detection

Detects objects in the given image using YOLO and applies non-maximum suppression to remove overlapping boxes.
start_image_object_detection

Handles the full pipeline: loading the image, running detection, and displaying the results.
📂 Resources
YOLOv4-Tiny Model: YOLOv4-Tiny Documentation
COCO Dataset Classes: List of classes available in resources/coco.names.txt.
📜 License
This project is licensed under the MIT License.

🌟 Acknowledgments
YOLO Framework: Developed by Joseph Redmon and the community.
OpenCV: For its robust computer vision utilities.

Enjoy exploring the power of real-time object detection! 💻✨
