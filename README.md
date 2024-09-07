# Medicinal_PLant_Detection_and_Classification

## Project Overview
This project focuses on the identification of Ayurvedic medicinal plants using **Convolutional Neural Networks (CNN)** based on deep learning. The project addresses the challenge of identifying various medicinal plants by their leaf images. With advancements in computer vision, this approach leverages CNN to accurately classify Ayurvedic plant species, thus assisting users in recognizing and making appropriate use of natural remedies.

## Objectives
- Use **CNN** to classify Ayurvedic medicinal plants based on leaf images.
- Develop a model that provides accurate identification without the need for extensive preprocessing.
- Help users understand the medicinal properties and benefits of identified plants.

## Features
- **Image Pre-processing**: Automatic handling of raw photo data without the need for manual feature extraction.
- **High Classification Accuracy**: Utilizes deep learning to ensure accurate classification of medicinal plants.
- **Web Application**: Interface to upload leaf images and receive classification results along with information on the plant’s medicinal benefits.
- **Database of Plants**: The model is trained on a diverse set of images collected from various sources.

## Methodology
1. **Data Collection**:
   - Gathered leaf images of Ayurvedic medicinal plants from various datasets (e.g., Kaggle).
   - Total dataset consists of 1,835 images, classified into 30 different plant species.
   
2. **Image Pre-processing**:
   - Applied image enhancement techniques, including contrast adjustment and noise reduction.
   
3. **Model Architecture**:
   - Built using **Convolutional Neural Networks (CNN)**.
   - Layers: Convolutional layers, Rectified Linear Units (ReLU), Pooling layers, Fully connected layers.
   - Model optimizes image recognition through hierarchical feature extraction.

4. **Training & Validation**:
   - **80%** of images used for training, **10%** for validation, and **10%** for testing.
   - Achieved **99% accuracy** in identifying Ayurvedic medicinal plants.

## How to Run
### Requirements
- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib

### Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/username/ayurvedic-plant-identification.git
