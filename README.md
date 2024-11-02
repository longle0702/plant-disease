# Plant Disease Classification with MobileNetV2

## Project Overview
This repository aims to classify plant diseases using MobileNetV2, a lightweight and efficient convolutional neural network architecture. My study focuses on detecting plant diseases from leaf images, supporting agricultural productivity and reducing dependency on manual inspections.

## Dataset
The project uses the [Plant Disease Recognition Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/plant-disease-recognition-dataset) from Kaggle. The dataset categorized into three classes:
- Healthy
- Rust
- Powdery

## Image Processing
The images are preprocessed with the following steps:
- Resize the image into 128 x 128.
- Convert the input images into RGB if needed.
- Convert to numpy arrays for efficient processing and compatibility with machine learning libraries like TensorFlow.

## Results
The model achieved high accuracy (95%), shows a well-balanced performance across all three classes, as indicated by Precision, Recall, and F1-Score.

