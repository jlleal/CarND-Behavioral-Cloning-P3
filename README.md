# Behavioral Cloning Project (Udacity Self-Driving Car Engineer Nanodegree)

The following project represents my solution to the Udacity Self-Driving Car Engineer Nanodegree Behavioral Clonning Project. 

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

# OverView

The project will take data collected from a car simulator and it will be used to train, evaluate and test the model.
The data consists in a series of images from the road taken from the center of the car, left and right side and a CSV file. 
The CSV file has data about the steering wheel angle corresponding to each of the center images. 

Note: The simulator is a tool developed by Udacity and it is not contained in this Repo. Also for obvious reasons the folder
data2 mentioned in the model.py file is not contained either. 

# Introduction

The project consists on using the data collected from the simulator as input for the ConvNet. This data will be used to 
train the network with the porpuse of teaching the car how to drive by itself. Note that only the steering angle is predicted. 
This uses the concepts and skills about Deep Learning, Convolutional Networks, Regularization Techniques for Overfitting, 
Activaition functions, etc leart during the entire course. 

Keras framework is used during this project. The output of the model is the model.h5 file contained in this Repo.
The drive.py script will open a connection with the simulator to be used in "autonomous mode" 
It will load the data (model.h5) to drive.

# Capturing Data

The final model has the intention to clone the driving behavior, so at the end the model will be as good as the driver that gathered the data. For this Udacity provided a simulator (see image below), this simulator allowed me to drive the car over a track. In order to have enough data for my model I decided to do the following driving patterns: 

- 1 and 1/2 laps driving clokwise
- 1 and 1/2 laps driving counter-clockwise
- some recovery drives from left to the center and right to the center. 



This data will be pre-processed in order to have even more data later before trainning the model. 
After capturing the data, I decided to divided in 2 sets: 80% for trainning and 20% for validation. 


# Model 

Udacity recommended to start by using Nvidia's model as a base and go from there. So I used the following model. 


# Results

... Coming Soon ...

