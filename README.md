# Neural-Network-Image-Classification
This repository contains a Convolutional Neural Network (CNN) model implemented for image classification on the LabelMe-12-50k dataset. The LabelMe-12-50k dataset consists of 50,000 JPEG images (40,000 for training and 10,000 for testing), which were extracted from LabelMe. Each image is 256x256 pixels in size. 50% of the images in the training and testing set show a centered object, each belonging to one of the 12 object classes shown in Table 1. The remaining 50% show a randomly selected region of a randomly selected image ("clutter").

The main focus of this project is to address the issue of class imbalance through techniques:
- WeightedRandomSampler
- Thresholding
- Undersampling.

The performance of the custom CNN is compared against a pretrained ResNet-18 model, evaluating the effectiveness of these strategies in improving classification results.
