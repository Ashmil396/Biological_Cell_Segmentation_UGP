Biological Cell Segmentation using CNN and U-Net

This repository presents a deep learning approach for automated biological cell segmentation from microscopy images. Two architectures, a custom Convolutional Neural Network (CNN) and a U-Net encoder–decoder network; were developed and evaluated for pixel-wise cell segmentation.

The project includes:

Image and mask preprocessing for supervised segmentation
Implementation of CNN and U-Net architectures
Skip Connections, BatchNormalization, MaxPooling2D, and Conv2DTranspose layers
Performance evaluation using Dice Score, IoU, Precision, Recall, and Pixel Accuracy
Comparative analysis between CNN and U-Net models

The U-Net model achieved 99.50% pixel accuracy, 99.52% precision, 99.40% recall, and a 99.46% Dice Score, demonstrating superior segmentation performance over the CNN baseline.
