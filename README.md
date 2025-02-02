# BRAIN-SEGMENTATION-PYTORCH

# Project Description :

This project presents an unsupervised anomaly detection framework for brain MRI segmentation, utilizing deep learning techniques such as Autoencoders (AEs), Variational Autoencoders (VAEs), and Generative Adversarial Networks (GANs). The framework is designed to detect neurological anomalies like multiple sclerosis (MS) and gliomas without relying on large labeled datasets.


# Purpose :

- The purpose of this study is to:

- Develop an unsupervised segmentation method for brain MRI anomaly detection.

- Reduce dependency on manually labeled datasets.

- Improve the accuracy of detecting neurological diseases such as MS and gliomas.


# Key Insights :

- Unsupervised Learning: Models are trained using only healthy brain MRI scans to learn normal anatomical patterns.

- Anomaly Detection: Deviations from learned patterns indicate potential anomalies.

- Comparative Model Analysis: Performance of AEs, VAEs, and f-AnoGANs (a specialized GAN for anomaly detection) was evaluated.

- High Accuracy: The VAE achieved 91.8% segmentation accuracy, while f-AnoGAN reached 85.2%, outperforming standard autoencoders.

- Clinical Application: Provides an efficient and scalable solution for medical diagnostics where labeled datasets are scarce.


# Dataset Details :

- The dataset includes MRI scans of:

- Healthy individuals

- Patients with MS lesions

- Patients with gliomas


# How to Use :

- Install the necessary dependencies.

- Load the dataset and preprocess MRI images.

- Train the autoencoder-based models using healthy MRI scans.

- Apply trained models to detect anomalies in new MRI scans.

- Evaluate performance using segmentation accuracy metrics.


# Prerequisites :

- Python 3.x

- TensorFlow / PyTorch

- OpenCV

- NumPy & Pandas


# Future Enhancements :

- Integration of real-time anomaly detection.

- Expansion of datasets to include more neurological disorders.

- Improvement in model interpretability for clinical applications.
