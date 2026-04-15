# Deep-Wide-Learning-Assistance-DeWi-for-Insect-Pest-Classification
DeWi is a deep learning–based insect pest classification system that combines discriminative learning using triplet loss with data augmentation for better generalization. It leverages CNNs and an efficient training strategy to improve accuracy and scalability for real-world agricultural pest detection.


This project presents DeWi (Deep-Wide Learning Assistance), a deep learning–based framework designed to improve the accuracy and robustness of insect pest classification. The system leverages advanced Convolutional Neural Networks (CNNs) combined with a novel training strategy to effectively learn both detailed (deep) and diverse (wide) feature representations of insect species.

The core idea behind DeWi is to enhance model performance from two key perspectives:

Discriminative Learning (Deep):
The model uses triplet margin loss to better distinguish between visually similar insect classes by learning more separable feature embeddings.
Generalization (Wide):
Through data augmentation techniques, the model improves its ability to handle variations in real-world data and scale across a large number of insect categories.

DeWi follows a one-stage alternating training strategy, allowing multiple neural networks to be jointly optimized for better feature extraction and classification performance.  


Hybrid deep + wide learning approach
Integration of triplet loss for improved feature discrimination
Strong generalization using data augmentation
Supports multiple CNN backbones (e.g., ResNet variants)
Automated training, validation, and testing pipeline
Designed for large-scale datasets like IP102


Technologies used:
Python
PyTorch
Convolutional Neural Networks (CNNs)
Deep Metric Learning (Triplet Loss)
Data Augmentation Techniques
