# Pneumonia Detection with ResNet-18

This repository implements a deep learning pipeline to classify chest X-ray images as **NORMAL** or **PNEUMONIA** using a fine-tuned ResNet-18 model. The project leverages PyTorch and includes a custom dataset loader, preprocessing steps, and training logic.

## Features
- **Custom Dataset Class**: Efficiently loads and preprocesses chest X-ray images.
- **Pre-trained ResNet-18**: Fine-tuned on the dataset for high classification accuracy.
- **Data Augmentation**: Includes resizing, normalization, and tensor conversion.
- **Training and Validation**: Tracks model performance during training and evaluation.

## Dataset
The dataset consists of chest X-ray images organized into three directories:
- `train/`: Training data
- `val/`: Validation data
- `test/`: Testing data

Each directory contains two subdirectories:
- `NORMAL/`: Images labeled as normal
- `PNEUMONIA/`: Images labeled as pneumonia

Ensure the dataset follows this structure for compatibility with the code.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pneumonia-detection.git
   cd pneumonia-detection
