# Intro to Image Classification

# Outline
Checkout the readme

In this notebook, we're going to explore the use of a few different ways of setting up an image classification model. The images labels are available: http://cs231n.stanford.edu/tiny-imagenet-200.zip. The training set contains 500 images for each of 200 different classes. The validation set contains 50 images for each of the 200 classes. You must download and unzip this file, putting the resulting directory in the same directory as your assignment notebook.
Each of the images is a 64x64 pixel image (4096) pixels, each with a rgb value, resulting in 12288 values describing each image.
First, we're going to load images from the tiny-imagenet-200 folder into a flattened format that is suitable for training any of the scikit-learn classifier models, such as a tree or logistic regression.
Later, we'll take advantage of data loading functions included in PyTorch that will preserve the 2D-shape of images and load batches instead of the entire training or validation set all at once.
