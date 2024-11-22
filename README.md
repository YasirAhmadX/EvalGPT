SkinFusionNet: A Hybrid Deep Learning Model for Skin Cancer Detection
📜 Description
SkinFusionNet is a hybrid deep learning model designed for efficient and accurate skin cancer detection. It integrates a lightweight Convolutional Neural Network (CNN) for feature extraction and a Random Forest Classifier (RFC) for final classification. The model is optimized for use with subsets of the ISIC 2024 dataset, providing a robust solution for early skin cancer detection, with particular attention to efficiency and computational scalability.

This repository includes:

Model architecture and training scripts.
Preprocessing techniques for handling dermoscopy images.
Benchmarking against existing state-of-the-art models.
Literature review of related works and how this model addresses existing challenges.
🚀 Features
Hybrid Approach: Combines CNN's feature extraction capabilities with RFC's interpretability and robustness.
Efficiency: Designed to work effectively on moderately powered systems with only 140 million MACs.
High Accuracy: Achieves competitive results with state-of-the-art methods while maintaining low computational cost.
Lightweight: Optimized for reduced inference time without compromising accuracy.
Scalability: Adaptable for different skin lesion classification tasks with minimal retraining.
📊 Performance
The model was tested on a subset of the ISIC 2024 dataset with the following results:

Accuracy: [Insert your model's accuracy]
Precision: [Insert precision]
Recall: [Insert recall]
F1 Score: [Insert F1 score]
📚 Dataset
Source: ISIC 2024 Dataset
The dataset was preprocessed to remove noise, resize images to 224x224 pixels, and balance class distributions.
🛠️ Setup and Usage
Prerequisites
Python >= 3.8
TensorFlow >= 2.0
Scikit-learn
NumPy
Matplotlib
