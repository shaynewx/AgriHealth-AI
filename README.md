# Leaf Disease Classification System

This repository hosts the code and documentation for our Leaf Disease Classification project. Our system uses advanced artificial intelligence methods to detect and classify leaf diseases, enhancing agricultural productivity and sustainability through early detection and accurate diagnosis.

## Introduction
Early and accurate classification of leaf diseases is crucial for optimizing crop health and yield. Traditional manual inspection is labor-intensive and prone to errors. Our AI-driven approach offers a promising solution by providing rapid, consistent, and accurate disease management, which is vital in large-scale farming environments.

## Project Summary
- **Models Used**: CNN, YOLOv10, ResNet18, VGG16
- **Key Techniques**: Transfer Learning, Data Augmentation, Majority Voting

## Models and Performance
We implemented various models including CNNs, ResNet18, VGG16, and YOLOv10, employing transfer learning and majority voting strategies to improve performance. Here is a brief overview of the model performances:
- **VGG16 (Pre-trained)**: Achieved the highest single model accuracy of 98.92%.
- **Majority Voting**: Utilized outputs from multiple models to achieve a robust accuracy of 99.197%.

## Dataset
The dataset used for training can be accessed here(https://data.mendeley.com/datasets/tywbtsjrjv/1). It consists of images labeled across 39 classes of plant leaf diseases.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Citation
If you use this system or the dataset in your research, please cite the relevant literature in the field of leaf disease classification.