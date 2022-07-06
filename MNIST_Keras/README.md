# MNIST Example USING KERAS

## MNIST (DATASET OF HANDWRITEN DIGITS)
MNIST is widely used dataset of handwritten digits that contain a number of handwritten digits for training a machine learning model and a number of handwritten digits for testing model. It was introduced in 1998 and has become a standard benchmark for classification task

## INTRODUCTION
MNIST data classification through implementation Convolutional Neural Network uisng Keras Libraries.

## llibraries

import numpy as np
import cv2
from mathplotlib import pyplot as plt
from keras.models import Sequential
from keras.layers import Dense, Dropout, Activation, Flatten
from keras.layers import Convolution2D, MaxPooling2D
from keras.util import np_util

## DATASET
from keras.datasets import mnist (MNIST dataset consist of 28c28 size image of handwritten digits)
