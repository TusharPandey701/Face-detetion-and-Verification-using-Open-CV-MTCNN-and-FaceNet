# Face Recognition and Verification Project

This project utilizes a deep learning-based facial recognition system to compare and verify faces from images. The system uses **MTCNN** (Multi-task Cascaded Convolutional Networks) for face detection and **FaceNet** for generating feature embeddings for face verification.

## Project Overview

The goal of this project is to create a system that can:
- Detect faces in images using MTCNN.
- Generate face embeddings using FaceNet.
- Compare two faces to determine whether they belong to the same person by measuring the cosine similarity between their embeddings.
- Provide a confidence score for the detected faces and similarity comparisons.

## Key Features

- **Face Detection**: Detect faces using the MTCNN model, which provides bounding boxes and keypoints such as eyes, nose, and mouth.
- **Face Embedding Generation**: Generate face embeddings (numerical feature vectors) using FaceNet.
- **Face Verification**: Compare faces by calculating the cosine distance between their embeddings.
- **Confidence Threshold**: Apply a confidence threshold for face detection and comparison to improve accuracy.

## Libraries Used

- **MTCNN**: Used for face detection.
- **FaceNet**: Used for face embedding generation.
- **OpenCV**: Used for image processing (e.g., reading and resizing images).
- **Matplotlib**: Used for visualization of the results.
- **NumPy**: For handling image data and numerical operations.
- **SciPy**: Used for cosine similarity calculation between face embeddings
