# Image-Classification🦋

This project aims to build and train a custom Convolutional Neural Network (CNN) from scratch using PyTorch for an image classification task. The original dataset can be found on the following link: https://www.kaggle.com/datasets/gpiosenka/butterfly-images40-species?resource=download&select=test . From the original dataset, I have created a subdataset taking into consideration the top 11 classes in terms of number of images. It consists of 1816 color images (224×224 pixels) of butterflies and moths, across 11 classes.

Given the limited data, the project emphasizes strategies to mitigate overfitting, including data augmentation and a carefully designed architecture.

Inspired by models such as GoogLeNet, the network will incorporate inception-style modules to capture multi-scale features, while deliberately avoiding simpler architectures like multilayer perceptrons or LeNet. The project workflow includes data preprocessing, designing the CNN, training it entirely from scratch, and evaluating its performance.
