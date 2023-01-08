# VGG_Image_Classification


## Introduction
we will be building VGG. We are building this CNN from scratch in PyTorch, and will also see how it performs on a real-world dataset.

We will start by exploring the architecture of VGG. We will then load and analyze our dataset, CIFAR-10, using the provided class from torchvision. Using PyTorch, we will build our VGG from scratch and train it on our data. Finally, we will see how the model performs on the unseen test data.

## VGG
VGG focuses on another crucial aspect of Convolutional Neural Networks (CNNs), depth. It was developed by Simonyan and Zisserman. It normally consists of 16 convolutional layers but can be extended to 19 layers as well (hence the two versions, VGG-16 and VGG-19). All the convolutional layers consists of 3x3 filters. You can read more about the network in the official paper.

![image](https://user-images.githubusercontent.com/101316217/210460665-27cd878c-3a2c-4daf-bd2c-a171cec5fe3d.png)


## Dataset
Let's start by loading and then pre-processing the data. For our purposes, we will be using the CIFAR10 dataset. The dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

Here are the classes in the dataset, as well as 10 random sample images from each:

![image](https://user-images.githubusercontent.com/101316217/211200710-2d7d1bbf-0375-4061-bf24-08eba1423d50.png)


## Tools
PyTorch

Colab

## Future Work
You can try using different datasets.

You can experiment with different hyperparameters and see the best combination of them for the model.

