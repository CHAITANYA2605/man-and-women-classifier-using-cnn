**Gender Classification using CNN with Keras**
This repository contains the code and data for a Convolutional Neural Network (CNN) model built with Keras, which classifies images of men and women. The model is trained on a dataset of images and demonstrates high accuracy in distinguishing between genders.

**Model Overview**
The CNN model was constructed using the Keras library, a high-level neural networks API, written in Python and capable of running on top of TensorFlow. The model architecture includes multiple convolutional layers, pooling layers, and dense layers to capture the features necessary for the classification task.

**Results**
The model was trained over 10 epochs, and the performance metrics for each epoch are as follows:

|Epoch|	Training| Accuracy|	Training| Loss|	Validation| Accuracy|	Validation Loss|
|-----|--------|--------|----------|----|-------|---------|----------|
1|	0.7422|	0.5048|	0.8713|	0.3604|
2|	0.8783|	0.2870|	0.8515|	0.3423|
3|	0.9129|	0.2170|	0.8911|	0.3159|
4|	0.9308|	0.1709|	0.9505|	0.2487|
5|	0.9508|	0.1311|	0.9010|	0.3509|
6|	0.9660|	0.0924|	0.8713|	0.3236|
7|	0.9763|	0.0672|	0.9208|	0.3435|
8|	0.9816|	0.0525|	0.8812|	0.3965|
9|	0.9868|	0.0389|	0.8614|	0.3985|
10|	0.9883|	0.0370|	0.9010|	0.5789|

**Best Accuracy**
*Best Training Accuracy: 0.9883
*Best Validation Accuracy: 0.9505
**Mean Accuracy**
*Mean Training Accuracy: 0.9278
*Mean Validation Accuracy: 0.8795
**Installation**
To run this project, clone the repository and install the required dependencies using pip

**License**
This project is licensed under the MIT License. See the LICENSE file for details.

**Acknowledgments**
Keras - The deep learning library used.
TensorFlow - The framework on which Keras runs.
Feel free to reach out if you have any questions or need further assistance!
