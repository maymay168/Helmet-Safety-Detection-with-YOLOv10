# Helmet Safety Detection with YOLOv10

A computer vision project for detecting safety helmets in images using the YOLOv10 model, built for safety compliance in industries like construction. This repository supports fine-tuning on custom datasets and real-time inference with pre-trained weights.

## Features

- Fine-tune YOLOv10 for tailored helmet detection
- High-precision inference on images
- GPU-accelerated training via cloud platforms
- Streamlined workflow for computer vision tasks

## Prerequisites

- Cloud environment like Google Colab (recommended for GPU)
- Basic knowledge of deep learning and object detection
- Git installed for repository cloning

## Getting Started

Follow these steps to set up and use the project:

### 1. Environment Setup

- Clone this repository to your local machine or cloud environment
- Install the YOLOv10 framework by cloning its official repository
- Set up required Python dependencies, ensuring compatible versions
- Restart the runtime in cloud environments to apply changes

### 2. Dataset Preparation

- Download a safety helmet dataset from a provided source (e.g., Google Drive)
- Extract the dataset to a working directory
- Verify that images and annotations are in YOLO-compatible format (e.g., with a `data.yaml` configuration)

### 3. Fine-Tuning the Model

- Obtain pre-trained YOLOv10 nano weights from the official release
- Configure training settings, such as epochs, batch size, and image size
- Execute the training process using the provided notebook to fine-tune the model
- Save the resulting weights for inference

### 4. Running Inference

- Load the fine-tuned model weights in the inference notebook
- Provide an input image (local file or URL) for helmet detection
- Set a confidence threshold (e.g., 0.3) to optimize detection accuracy
- Generate and visualize bounding boxes on detected helmets

## Results

- Robust helmet detection suitable for safety monitoring
- Example outputs with annotated bounding boxes available in the inference notebook
