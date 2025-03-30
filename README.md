# Vehicle Spare Parts Segmentation Using YOLOv11

## Overview
This project demonstrates how to train **YOLOv11** for **vehicle spare parts segmentation** using the Ultralytics framework. The model is trained on a custom dataset to detect and segment various car parts efficiently.

## Features
- **Accurate segmentation** of vehicle spare parts
- **YOLOv11-based** model for real-time inference
- **Custom dataset training** using Ultralytics YOLO
- **Automated vehicle inspection and damage assessment**

## Dataset & Training
- The dataset consists of labeled vehicle images with segmented parts.
- The model was trained using **Ultralytics YOLOv11**.
- The notebook includes preprocessing, model training, and evaluation steps.

## Repository Files
- **how_to_train_ultralytics_yolo_on_carparts_segmentation_dataset.ipynb**  
  Jupyter notebook with complete steps to train YOLOv11 on the custom dataset.

- **predicted.png**  
  Sample image showing the segmentation results of vehicle spare parts using the trained model.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/muhammadrizwan11/how-to-train-ultralytics-yolo-on-carparts-segmentation-dataset.git
   cd how-to-train-ultralytics-yolo-on-carparts-segmentation-dataset
   ```
2. Install dependencies:
   ```bash
   pip install ultralytics opencv-python numpy
   ```
3. Open the Jupyter notebook and follow the training steps:
   ```bash
   jupyter notebook how_to_train_ultralytics_yolo_on_carparts_segmentation_dataset.ipynb
   ```
4. Run inference using the trained model and visualize the results.

## Results
The model successfully segments various vehicle parts with high accuracy, as shown in **predicted.png**.

## Applications
- **Automated Vehicle Inspection**: Identify car parts for damage assessment.
- **Insurance & Claims Processing**: Speed up claim approvals using AI-powered damage analysis.
- **Quality Control in Manufacturing**: Detect defects in car parts automatically.

## Contributing
Feel free to contribute by improving the model or dataset.

## License
This project is open-source and available under the MIT License.

---
### Author: Muhammad Rizwan

