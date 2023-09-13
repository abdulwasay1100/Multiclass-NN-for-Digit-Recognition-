# Multiclass-NN-for-Digit-Recognition-

# Neural Networks:

I've implemented a neural network to do binary classification. I extend that to multiclass classification. This will utilize the softmax activation.

# Problem Statement:

In this assignment, I've used a neural network to recognize ten handwritten digits, 0-9. This is a multiclass classification task where one of n choices is selected. Automated handwritten digit recognition is widely used today - from recognizing zip codes (postal codes) on mail envelopes to recognizing amounts written on bank checks.


# Dataset:

The load_data() function shown below loads the data into variables X and y

The data set contains 5000 training examples of handwritten digits 
Each training example is a 20-pixel x 20-pixel grayscale image of the digit.
Each pixel is represented by a floating-point number indicating the grayscale intensity at that location.
The 20 by 20 grid of pixels is “unrolled” into a 400-dimensional vector.
Each training examples becomes a single row in our data matrix X.
This gives us a 5000 x 400 matrix X where every row is a training example of a handwritten digit image.
The second part of the training set is a 5000 x 1 dimensional vector y that contains labels for the training set
y = 0 if the image is of the digit 0, y = 4 if the image is of the digit 4 and so on.

This is a subset of the MNIST handwritten digit dataset (http://yann.lecun.com/exdb/mnist/)
