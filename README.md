# Image Recognition

## Introduction
In this project, you'll classify images from the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. The dataset consists of airplanes, dogs, cats, and other objects. You'll preprocess the images, then train a convolutional neural network on all the samples. The images need to be normalized and the labels need to be one-hot encoded. You'll get to apply what you learned and build a convolutional, max pooling, dropout, and fully connected layers. At the end, you'll get to see your neural network's predictions on the sample images.

## Software/Tools
[TensorFlow](https://www.tensorflow.org)
We will be using TensorFlow™, an open-source library developed by Google, to build deep learning models throughout the course. Coding will be in Python 2.7 using iPython notebooks, which you should be familiar with.

Download and Setup
Method 1: Pre-built Docker container with TensorFlow and all assignments
To get started with TensorFlow quickly and work on your assignments, follow the instructions in this README.

Note: If you are on a Windows machine, Method 1 is your only option due to lack of native TensorFlow support.

-- OR --

Method 2: Install TensorFlow on your computer (Linux or Mac OS X only), then fetch assignment code separately
Follow the instructions to download and setup TensorFlow. Choose one of the three ways to install:

Pip: Install TensorFlow directly on your computer. You need to have Python 2.7 and pip installed; and this may impact other Python packages that you may have.
Virtualenv: Install TensorFlow in an isolated (virtual) Python environment. You need to have Python 2.7 and virtualenv installed; this will not affect Python packages in any other environment.
Docker: Run TensorFlow in an isolated Docker container (virtual machine) on your computer. You need to have Vagrant, Docker and virtualization software like VirtualBox installed; this will keep TensorFlow completely isolated from the rest of your computer, but may require more memory to run.
