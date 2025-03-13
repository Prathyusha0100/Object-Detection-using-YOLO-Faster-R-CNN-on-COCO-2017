# Object Detection using YOLO & Faster R-CNN on COCO 2017 (Person Only)  

This project implements **object detection** for identifying **persons** in images using the **COCO 2017 dataset**. The model is trained using **YOLO or Faster R-CNN**, and performance is evaluated using **Intersection over Union (IoU)**.

## Project Overview  
- **Dataset:** Extracted the **'person' class** from **COCO 2017**.  
- **Train-Test Split:** Created a **custom train-test separation**.  
- **Model Used:** YOLO / Faster R-CNN for **real-time object detection**.  
- **Performance Metric:** **IoU (Intersection over Union)** for accuracy assessment.  

## Features  
**Dataset Processing:**  
- Filtered **only 'person' category** from COCO 2017 dataset.  
- Created **custom train-test split**.  

**Object Detection Models:**  
- Implemented **YOLOv5 / YOLOv8** for **fast, real-time detection**.  
- Used **Faster R-CNN** for **high-accuracy detection**.  

**Evaluation & Performance:**  
- Computed **IoU (Intersection over Union)** for accuracy assessment.  
- Visualized predictions with **bounding boxes**.  

## Installation & Setup  
To set up and run the project locally:  

1. **Clone this repository:**  
   ```bash
   git clone https://github.com/your-username/Object-Detection-COCO.git
   cd Object-Detection-COCO
2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
3. **Download COCO Dataset:**
   ```bash
   python dataset_preparation.py
4. **Train the Object Detection Model:**
   ```bash
   python train.py --model yolo --epochs 50
5. **Run the Model on Test Data:**
   ```bash
   python test.py --model yolo
## Dataset ##
  Source: [COCO 2017 Dataset](https://cocodataset.org/)
  Filtered Class: Person (only).

## Results ##
  Object Detection Accuracy using IoU.
  Visualized bounding boxes on test images.

