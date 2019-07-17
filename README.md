Problem Statement

A home electronics company that manufactures state of the art smart televisions want to develop a cool feature in the smart-TV that can recognize five different gestures performed by the user which will help users control the TV without using a remote. Let's have professor Raghavan introduce you to the problem statement: The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command: •	Thumbs up: Increase the volume • Thumbs down: Decrease the volume •	Left swipe: 'Jump' backwards 10 seconds •	Right swipe: 'Jump' forward 10 seconds
•	Stop: Pause the movie Some important fact about data:

Each video is a sequence of 30 frames (or images).
There are 666 videos provided as training data and 100 videos provided as validation data
all images in a particular video subfolder have the same dimensions
different videos may have different dimensions. Specifically, videos have two types of dimensions - either 360x360 or 120x160
There are two csv(one for train, one for validation) files having path of videos Our task is to train a model on the 'train' folder which performs well on the 'val' folder as well Thus, there are two types of architecture commonly used for analysing videos, both explained below.
Convolutions + RNN
3D Convolutional Network, or Conv3D


Objective :

Generator Write code for generator function so, that it can provide data in batch while training model. Also, write code for preprocessing image files in generator function
Model Create models with two architectures
Convolution 3D
Convolution 2D + RNN a.	RNN with LSTM b.	RNN with GRU
Output Tune model to achieve good accuracy on train as well as validation data Provide all metric with changes done in model to tune it in the write up

Dataset was provided by institute. Hence, i cannot share it here. But you can try this notebooks with any dataset that having criteria listed below:

Each video is a sequence of 30 frames (or images).
all images in a particular video subfolder have the same dimensions
different videos may have different dimensions. Specifically, videos have two types of dimensions - either 360x360 or 120x160
There are two csv(one for train, one for validation) files having path of videos

Link is here : https://drive.google.com/file/d/1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL/view
