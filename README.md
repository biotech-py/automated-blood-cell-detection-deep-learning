![Python](https://img.shields.io/badge/Python-3.10-blue)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-green)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-red)
![Gradio](https://img.shields.io/badge/Gradio-Web_App-orange)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Spaces-yellow)

---

## Live Demo

🔗 Hugging Face Space:

https://huggingface.co/spaces/nirupam-joarder/blood-cell-detector

---

# 🩸 Automated Blood Cell Detection and Classification using Deep Learning

## Overview

This project presents a deep learning-based system for automated detection, classification, and counting of blood cells from microscopic blood smear images. The model is built using YOLOv8 and deployed as an interactive web application using Gradio and Hugging Face Spaces.

The system can identify multiple blood cell types, visualize detections with bounding boxes, and provide automated cell count summaries.

---


## Features

* Automated blood cell detection
* Multi-class blood cell classification
* Cell counting and summary generation
* Bounding box visualization
* Interactive web interface
* Cloud deployment using Hugging Face Spaces

---

## Blood Cell Classes

The model is trained to detect the following blood cell types:

* Basophil
* Eosinophil
* Erythroblast
* Immature Granulocyte (IG)
* Lymphocyte
* Monocyte
* Neutrophil
* Platelets

---

## Dataset

The model was trained on a blood cell microscopy dataset containing:

- Basophil
- Eosinophil
- Erythroblast
- Immature Granulocyte (IG)
- Lymphocyte
- Monocyte
- Neutrophil
- Platelets

Images were annotated in YOLO format and used for object detection training.

---

## Technology Stack

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* Gradio
* Hugging Face Spaces

---

## Workflow

1. Upload a blood smear image.
2. YOLOv8 performs cell detection.
3. Detected cells are classified.
4. Bounding boxes are displayed.
5. Cell counts are summarized automatically.

---

## Project Screenshots

### Homepage

![Homepage](homepage.jpeg)

### Blood Cell Detection

![Detection Result](detection_result.jpeg)

### Negative Test

![Negative Test](negative_test.jpeg)

---

## Deployment

The project is deployed on Hugging Face Spaces and can perform real-time blood cell detection through a web interface.

---

## Model Status

Current version is a proof-of-concept trained for 20 epochs.

The model successfully performs blood cell detection and classification but may produce misclassifications due to limited training duration.

Future improvements:
- Train for 100+ epochs
- Increase dataset size
- Hyperparameter tuning
- Cross-validation
- Improved classification accuracy
- Confidence threshold controls
- Batch image processing

---


## Author

**Nirupam Joarder**

Biotechnology Graduate
National Institute of Technology Rourkela
