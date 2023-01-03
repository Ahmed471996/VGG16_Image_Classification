# VGG_Image_Classification


## Introduction
we will be building VGG. We are building this CNN from scratch in PyTorch, and will also see how it performs on a real-world dataset.

We will start by exploring the architecture of VGG. We will then load and analyze our dataset, CIFAR-100, using the provided class from torchvision. Using PyTorch, we will build our VGG from scratch and train it on our data. Finally, we will see how the model performs on the unseen test data.

## VGG
VGG focuses on another crucial aspect of Convolutional Neural Networks (CNNs), depth. It was developed by Simonyan and Zisserman. It normally consists of 16 convolutional layers but can be extended to 19 layers as well (hence the two versions, VGG-16 and VGG-19). All the convolutional layers consists of 3x3 filters. You can read more about the network in the official paper.

![image](https://user-images.githubusercontent.com/101316217/210460665-27cd878c-3a2c-4daf-bd2c-a171cec5fe3d.png)


## Dataset
we'll be using the CIFAR-100 dataset. This dataset is just like the CIFAR-10, except it has 100 classes containing 600 images each. There are 500 training images and 100 testing images per class. The 100 classes in the CIFAR-100 are grouped into 20 superclasses. Each image comes with a "fine" label (the class to which it belongs) and a "coarse" label (the superclass to which it belongs). We'll be using the "fine" label here. Here's the list of classes in the CIFAR-100:

![image](https://user-images.githubusercontent.com/101316217/210460412-4a5caada-b6e1-4896-8126-e701954369e5.png)


## Tools
PyTorch

Colab

## Future Work
You can try using different datasets.

You can experiment with different hyperparameters and see the best combination of them for the model.

