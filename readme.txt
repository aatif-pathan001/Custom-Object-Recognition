#DL2-T8-Projects

# Custom Object Recognition

# Team Members:-
1. Aatif khan pathan - 18EJIEE001
2. Shourabh Mathur - 18EJIEE043
3. Mahjhbee  - 18EJIEE030

# Language: Python

# Platform used : Jupyter Notebook

# Zip file:-
 Python source code(in IPYNB format)

# Libraries Used:-
 1. numpy - Using numpy ,mathematical and logical operations on arrays can be performed
 2. matplotlib - pandas is a Python library that is used for fast data analysis data cleaning and data preprocessing
 3. pandas - Matplotlib is comprehensive library for creating static animated and interactive visualisation in Python
 4. keras -  Designed to enable fast experimentation with deep neural networks, it focuses on being user-friendly, modular, and extensible. 
 5. tensorflow - Its flexible architecture allows for the easy deployment of computation across a variety of platforms (CPUs, GPUs, TPUs), and from desktops to clusters of
                 servers to mobile and edge devices.
 7. cv2 - OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products.
 8. OS - The OS module in Python provides functions for interacting with the operating system. OS comes under Python’s standard utility modules
 9. tqdm_notebook - Python/Jupyter Notebook progressbar decorator for iterators. Includes a default range iterator printing to stderr.
 10.  scikit-learn - The sklearn library contains a lot of efficient tools for machine learning and statistical modeling including classification, regression and clustering.

# Table of contents:
 1. Importing necessary libraries
 2. Capturing Multiple Images of an Object
 3. Loading Data
 4. Split Data into Train and Test
 5. Designing Model
 6. Training Model
 7. Evaluation
 8. Confusion Matrix
 9. Predicting
 10. Capturing Image for Prediction 


# Brief of project: 
Detecting objects in images is a hot research topic and really useful in practice. The advancement in Computer Vision (CV) and Deep Learning (DL) made training and running object detectors possible for practitioners of all scale. Modern object detectors are both fast and much more accurate (actually, usefully accurate).
in this project we will learn how to prepare a custom dataset and use a library for object detection based on TensorFlow and Keras. Along the way, we’ll have a deeper look at what Object Detection is and what models are used for it.

The task we’re going to work on is we will detect raw images. 
our model will capture multiple images of an object
our model will train a fair bit of preprocessing. training is needed to convert the data into the format that Keras Retina understands.
then our model will load the data and Define the number of classes( ball , book , clock , human , schoolbag , smartphone and sunglasses)
then our model will split the data into train and test
then our model will Design the CNN Sequential model with Convolution2D and MaxPooling2D
then our model will evaluate Test loss and test Accuracy
our model will Compute the confusion matrix
then finally our model will Capture Image for Prediction and predict the object shown.