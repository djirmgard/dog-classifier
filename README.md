[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

In this project I designed and trained a Convolutional Neural Network (CNN) algorithm for image recognition of dogs.  Given an image of a dog, the algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

I also used pre-trained networks such as Haar feature-based cascade classifiers from [OpenCV](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html) for human face recognition and the VGG16 model developed by the [University of Oxford](https://neurohive.io/en/popular-networks/vgg16/) and adapted them for the use in this project.

The end result is a model that can be deployed in a web app that takes an image as input and (1) comments whether it identified a human, dog, or neither of the two in the picture and (2) predicts the breed that the dog (OR human) resembles the most. The model has an accuracy of over 70% when performing on a test sample which can still be improved further.

## Data & Libraries

Data used comprises over 13,000 images of humans and over 8,000 images of dogs and were provided by Udacity plus a selection of images provided by me. I used PyTorch to design and train the neural network plus a number of standard libraries such as numpy, PIL, and tgdm to handle the images.

## Content

The repository consists of the project's Jupyter Notebook, a sample of images, as well as the project report.

