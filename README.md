Project Overview

This project aims to enhance botnet detection using Generative Adversarial Networks (GANs) and Wasserstein GANs (WGANs) for generating realistic synthetic network traffic data. By leveraging the CTU-13 dataset, this approach seeks to address the data imbalance and improve the robustness of intrusion detection systems (IDS) against evolving botnet threats.

Key Features

Synthetic data generation using GANs and WGANs.

Multi-class classification for various botnet families.

Detailed analysis of classifier performance.

Comparative evaluation of real and synthetic data.

Dataset

The CTU-13 dataset is a widely used benchmark for botnet detection. It contains network traffic captures from real-world botnet attacks, providing a challenging environment for IDS model evaluation. Key characteristics include:

13 different botnet scenarios.

Imbalanced class distribution.

Complex, high-dimensional data.

Methodology

Data Preprocessing:

Extracted botnet, normal, and background traffic flows.

Feature selection to reduce noise and focus on critical attributes.

Handling class imbalance using oversampling and data augmentation.

Synthetic Data Generation:

Trained GAN and WGAN models on CTU-13 data to generate realistic network traffic.

Implemented Wasserstein loss and weight clipping for stable WGAN training.

Classifier Training and Evaluation:

Trained classifiers like Logistic Regression, Linear SVC, Decision Tree, and Extra Trees on both real and synthetic data.

Evaluated models using accuracy, precision, recall, F1-score, and log loss.

Performance Analysis:

Assessed model robustness using synthetic data as both training and test inputs.

Conducted multiclass classification to evaluate generalization capability.

