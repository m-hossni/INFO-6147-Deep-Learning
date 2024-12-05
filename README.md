# INFO-6147-Deep-Learning
this reporitory contains Deep Learning course project for AIM2 program at Fanshawe college Fall 2024

# Introduction
Image classification tasks are important part of computer vision which is used in various applications. This project aims to create an image classification model using convolutional neural network (CNN) and then compare its results with state of the art models available on the web. The dataset that is used in this project is Tiny ImageNet. 

# Objective
The objective of this project is to create a classifier with reasonable accuracy on Tiny ImageNet dataset. Additionally, transfer learning will be used to compare the model which is made from scratch to the industry state of the art models.

# Dataset Description
Tiny ImageNet dataset is a group of colored images with 200 classes. The dataset contains 100,000 samples with balanced distribution of 500 images per class for training (50 for validation and 50 for testing). The images in this dataset are of size 64X64X3.

![b7km9pkp](https://github.com/user-attachments/assets/bdd062a6-0e70-4862-bb4d-330b4b374c86)



# Methodology
The methodology for classification in this project will be conducted using CNN. CNNs can capture spatial information with filters and they would be the appropriate candidates for this task. 
Multiple network designs will be studied to find an optimal design. Additionally, the results will be compared to a pretrained model (Resnet) with transfer learning.

# Limitations
Since the dataset contains 200 classes and images with size of 64X64X3, computational resources may present a bottleneck in the study. Thus, in case these limitations are faced, the number of classes studied will be reduced to speed the process.

# Additional Work
If time permits, the backbone of the network developed for classification task will be used to create an Autoencoder. The goal is to use the pretrained model and the Latent vectors to create masked images from the input. This will be done using the model filters to extract model activation maps which will be compared with the generated image from the decoder.
The final product should have the following network design.

![image](https://github.com/user-attachments/assets/a0426285-a6a1-4818-9a8b-0c481bb325b8)


