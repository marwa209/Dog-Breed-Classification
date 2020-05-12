# Dog-Breed-Classification
Convolutional Neural Network ( CNN) to detect and classify dogs in images

# Project Overview
This is my second project i did in the Deep learning Nanodegree of Udacity using Convolutional Neural Network. In this project, I have learned how to build a pipeline to process real-world, user-supplied images. Given an image of a dog, my algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

# Problem
Statement: Having dataset of human faces and dataset for dog images, the Network is trained to detect the human and dogs in images and gives percentage of the accuracy of the trained model in terms of how many images in the human dataset are detected to be human face and how many images in dog dataset are detected to have dogs.
CNN architecture of trained model attains at least 10% accuracy on the test set

Using CNN and the trained model, another job is done which is classifying the dog's breed in each image and if a human is detected, the resembling breed shall be classified.

Also a new concept is introduced which is the transfer learning using a pretrained model as VGG16 and modifying some of its layers to be used in classification task. CNN to Classify Dog Breeds from Scratch attains at least 10% accuracy on the test set. However, CNN to Classify Dog Breeds Using Transfer Learning has accuracy of atleast 60%.

# Python Libraries and Prerequisites
* Python 3.7
* Numpy
* Pandas
* Matplotlib
* Jupyter Notebook
* Torchvision
* PyTorch

# Installing 
* conda install -c conda-forge numpy
* conda install -c conda-forge pandas
* conda install -c conda-forge matplotlib
* pip install torchvision
* conda install -c pytorch pytorch

# Project Structure

this projects run on jyputer notebook and the output is dog-app.ipynb which contains the output of running the code a

dog-app.ipynb - Main project file

dog-app.html - the main project in html format

images : Tthe dataset of dogs



