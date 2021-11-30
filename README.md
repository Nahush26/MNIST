
# MNIST Digit Recognizer

The purpoe of this prroject is to create a machine learning model
to identify handwritten digits. The project uses the MNIST handwritten
digits database to train , validate and test our model. 

# More on Data:

The MNIST database of handwritten digits has a training set of 
60,000 examples, and a test set of 10,000 examples. It is a 
subset larger set available from NIST. The digits have been 
size-normalized and centered in a fixed-size image.
In this projects the 60,000 train images have been split into
a train set and a validation set of ratio 11:1 respectively.
The images are 28x28 pixels grayscale images.

# PyTorch

This project uses Module from the PyTorch framework to build the convolutional
neural network model that we will be using . 

# Model

The model is comprised of 2 convolutional blocks with skip
connections followed by 2 fully connected layrs.
Crossentropy loss function has been used at the end.
The used optimzer is adam and the learning rate scheduler is based on
number of epochs. 

# Results
The metric used for evaluation is accuracy.

The model performs as follows :
Training data :   99.98% 

Validation data : 99.38%

Test data :       99.29%