# Quantum-Computing-Project
# Pneumonia Detection using Quantum Transfer Learning
This repository contains the implementation of a hybrid quantum-classical machine learning model for detecting pneumonia from chest X-ray images. By leveraging Quantum Transfer Learning, the project combines the strengths of quantum computing and classical deep learning to improve medical image classification.

## Overview
Pneumonia is a significant global health challenge, particularly in children and the elderly. This project explores the use of Quantum Neural Networks (QNNs) in conjunction with pre-trained classical models like VGG16 to develop an efficient and accurate diagnostic tool.

## Features
* Hybrid Architecture: Combines classical pre-trained models (e.g., VGG16) with quantum layers for feature extraction.
* Quantum Transfer Learning: Uses PennyLane for simulating quantum circuits integrated into the model pipeline.
* Dataset: Chest X-ray dataset containing labeled images for pneumonia and normal cases.
* Performance Metrics: Evaluates accuracy and computational efficiency in both classical and quantum models.

## Dataset
The dataset used is the Chest X-Ray Images dataset from Kaggle. It consists of:

5,863 X-ray images classified as Pneumonia or Normal.
Separate folders for training, validation, and testing.

## Methodology
* Classical Transfer Learning: A pre-trained VGG16 model is fine-tuned on the chest X-ray dataset.
* Quantum Layer Integration: A quantum layer is added using PennyLane's hybrid framework to extract additional features.
* Training & Evaluation: The hybrid model is trained and evaluated for classification accuracy and compared with classical counterparts.

## Tools and Technologies
* Python
* PennyLane: For quantum computing simulations.
* TensorFlow/Keras: For classical deep learning.
* NumPy, Matplotlib: For data preprocessing and visualization.

## Results
Demonstrated the feasibility of integrating quantum layers into traditional models.
Achieved competitive accuracy, showing the potential of quantum computing in medical applications.

## Future Work
Optimize quantum circuit designs for better performance.
Explore scalability using quantum hardware.
Expand the methodology to other medical imaging applications.

## References
* https://aanshsavla.hashnode.dev/pneumonia-detection-using-quantum-transfer-learning
* https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
* https://pennylane.ai/qml/demos/tutorial_quantum_transfer_learning
