# Facial_Keypoint_Detection

This project was done as a part CS-574 (Computer Vision using Machine Learning) course at IIT Guwahati.

## Dependencies
1. Numpy
2. Python 3.6
3. Keras(with Tensorflow Backend)
4. Pandas
5. Scikit-Learn

## Architectures 
We have tried out 4 types of Architecture namely :
1) RandomForest
   * Data was split into 33% test data and 77% training data.
   * RMSE = 2.02725802
2) Feed-forward Neural Network (with single hidden layer of 100 neuron)
   * Data was split into 33% test data and 77% training data.
   * RMSE = 2.71529003976
   * Some result on test data: 
   * ![alt text](http://danielnouri.org/media/kfkd/samples1.png)
3) Convolutional Neural Network 
   * Following architecture was used for the experiment :
   * ![alt text](dataset/save.PNG)
4) Convolutional Neural Network (with dropout on every layer)

## Project Members
1. Abhinav Anshuman
2. Aditya Gaurav
3. Chirag Sodani
4. Rahul Kumar
