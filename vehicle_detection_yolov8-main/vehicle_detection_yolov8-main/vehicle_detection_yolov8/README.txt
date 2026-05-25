# 🚗 Vehicle Detection and Traffic Density Estimation using YOLOv8

## Overview
This repository contains an **end-to-end computer vision pipeline** for vehicle detection and traffic density estimation using **YOLOv8**.  
The project demonstrates the complete workflow starting from image upload and pretrained inference, passing through smart dataset generation and model training, and ending with evaluation, analysis, and model export for deployment.

The project is designed as a **Master-level academic and portfolio project**, focusing on system understanding, reproducibility, and practical implementation rather than large-scale benchmarking.

---

## Objectives
- Detect vehicles (cars, buses, trucks, motorcycles) from images.
- Estimate traffic density based on detected vehicle counts.
- Automatically generate YOLO-format labels using a pretrained model (smart labeling).
- Create a custom dataset with train/validation splits.
- Train YOLOv8 models with different hyperparameter configurations.
- Evaluate and compare trained models.
- Analyze performance using metrics and visualizations.
- Export trained models for deployment (ONNX).

---

## Key Features
- Pretrained YOLOv8 inference
- Smart / pseudo-label generation
- Automatic dataset creation (YOLO format)
- Hyperparameter tuning experiments
- Advanced training with learning-curve analysis
- Comprehensive model evaluation
- Performance visualization
- ONNX model export

---

## Project Structure

---

## Environment & Requirements
- Platform: Google Colab
- Python: 3.x
- Libraries:
  - PyTorch
  - Ultralytics YOLOv8
  - OpenCV
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn

All required dependencies are installed directly inside the notebook.

---

## Workflow
1. Environment setup and imports  
2. Upload vehicle images  
3. Vehicle detection using pretrained YOLOv8  
4. Smart label generation  
5. Dataset creation (train/validation split)  
6. Model initialization  
7. Hyperparameter tuning and training  
8. Advanced training and results analysis  
9. Model evaluation and comparison  
10. Performance analysis and visualization  
11. Model export for deployment (ONNX)

---

## Evaluation Metrics
- Precision
- Recall
- mAP@0.5
- mAP@0.5:0.95
- Average confidence score
- Vehicle count distribution

---

## Limitations
- Dataset size depends on manually uploaded images.
- Results are intended for demonstration and learning purposes.
- Not designed for large-scale benchmarking or production deployment.

---

## Academic Context
- Level: Master’s Degree (Artificial Intelligence / Computer Vision)
- Purpose: Academic portfolio and project showcase
- Focus: End-to-end pipeline design and practical understanding of object detection systems

---

## Future Work
- Integration with public traffic datasets for benchmarking
- Video-based traffic analysis
- Real-time inference
- Edge and TensorRT deployment
- Cross-dataset generalization studies

---

## Author
**Saad Talaq Alsulami**  
Master’s Student in Artificial Intelligence  

---

## License
This project is provided for educational and research purposes.
