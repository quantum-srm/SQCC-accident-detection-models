# YOLOv11-Based Fire Detection System

## Introduction and Overview
This project utilizes **YOLOv11**, a state-of-the-art object detection model, to identify fire in various contexts, including **images, videos, and live webcam feeds**. YOLOv11 offers advancements in detection accuracy, speed, and scalability, making it ideal for real-time applications in safety monitoring and disaster prevention.

## Project Implementation

### 1. **Dataset Preparation**
The model is trained using a curated dataset of fire images, with annotations tailored for object detection. Tools like **Roboflow** were used for preprocessing and augmentation.

### 2. **Model Configuration**
The base model, `yolo11n.pt`, is fine-tuned on the fire dataset. The configuration was optimized to balance performance and computational efficiency.

### 3. **Training and Validation**
The model was trained with:
- **Hyperparameters**: Tuned for optimal performance on the fire dataset.
- **Loss Functions**: To ensure accurate localization and classification.
- **Validation**: A separate dataset was used to evaluate performance and adjust parameters.

### 4. **Inference and Testing**
The trained YOLOv11 model demonstrates robust fire detection on:
- **Static Images**: Quick identification of fire in photos.
- **Video Feeds**: Continuous detection in surveillance footage.
- **Live Webcam Feeds**: Real-time fire detection for dynamic scenarios.

## Results and Performance
The YOLOv11 fire detection system achieves high precision and recall, ensuring reliable identification across different environments.

### Example Use Cases
- Fire monitoring in forests and remote areas.
- Industrial safety inspections.
- Enhancing smart surveillance systems.

