# PyTorch-CIFAR10-Image-Classification

This project is the implementation of image classification using image classification transfer learning techniques on the images available in CIFAR-10 Dataset using PyTorch Technology․ The project is built as a part of my proposal for application at the Mitacs Globalink Research Internship․


# Project Summary


Aim: Develop a Deep Learning Image Classifier and tune and assess the model․


Dataset: The CIFAR-10 dataset‚ which has 60000 colored images of 32x32 resolution divided among 10 classes․


Framework Used: PyTorch‚ Torchvision‚ and Google Colab (T4 GPU Accelerated)


# Model Architecture and Training


Architecture: ResNet18 with pre-trained weights


Augmentation Technique: To augment the model‚ RandomCrop (size=32 and padding=4) and RandomHorizontalFlip were used during the model training․


As for the models‚ a Batch Size of 64‚ the optimal number of epochs‚ Cross-Entropy Loss‚ and Adam/SGD optimizer were used․


# Results and Assessment

Final assessment value achieved in testing: 82.45% calculated based on 10000 images.


Performance Note: This number proves that the model can be treated as a reliable basis for evaluating undergraduate research practices with regard to its generalization abilities.


Tips About How to Execute the Code


Use the file named PyTorch-CIFAR10-Image-Classification.ipynb and copy it
