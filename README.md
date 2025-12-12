# Plastic Bottle Detection — Object Detection Using Custom Dataset

This project focuses on detecting **plastic bottles** in images using a custom dataset and an object detection model (YOLO-based / Faster R-CNN style).  
The notebook includes **dataset cleaning, preprocessing, training, and inference visualization**. The goal is to automate waste detection and support intelligent recycling or sorting systems.

---

## Features
- Custom dataset cleaning & preprocessing  
- Object detection model (YOLO-style pipeline)  
- Training loop included inside the notebook  
- Inference script to visualize bounding boxes  
- Uses OpenCV for image processing  
- Generates output images with detected bottles  

---

## Project Structure
plastic-bottle-detection/
├── BOTTLEDETECTION.ipynb # Main notebook
├── data/
│ ├── images/ # Training/testing images
│ └── annotations/ # Bounding-box labels (XML / TXT)
├── checkpoints/ # Saved model weights
├── outputs/ # Inference results (images with boxes)
├── requirements.txt
├── train.py # (Optional) Training script
├── inference.py # (Optional) Inference script
└── README.md

## Dataset
This project uses a custom dataset containing images of plastic bottles.
Each image has corresponding annotation files (YOLO TXT / PASCAL VOC XML) with bounding-box coordinates.

data/
├── images/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── annotations/
    ├── image1.xml / txt
    ├── image2.xml / txt
    └── ...

## Technologies Used
Python
OpenCV (cv2)
NumPy
Matplotlib
YOLO-style detection pipeline
(Optional) PyTorch / TensorFlow depending on your code
