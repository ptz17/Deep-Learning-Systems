# Task 1
# Re-do Lab 1 Task 1 (dataset-1.csv) using Tensorflow Keras package 

Requirement:  
  a) Build a two layer model using tf.keras.models.Sequential, and use linear act function in HIDDEN layer 
  b) Using default SGD optimizer for training.
  c) Evaluate your model using model.evaluate
  d) Repeat training and testing by adding ReLU act in your HIDDEN layer 

# Task 2 
Image classifier (MNIST) using ConvNet 

Requirement: 
  a) Build ConvNet model using Tensorflow Keras package
  b) Use tf.keras.models.Sequential to build a Conv -> MaxPool -> Conv -> MaxPool -> Dense -> Dense model.
      print out your ConvNet using model.summary
  c) Train your model using TWO different optimizers, and Evaluate your models using model.evaluate
  d) Evalaute single image using model.predict. 
    Specifically, plot out the input image in Jupyter, print the output of model.predict, and finalize the label


# Task 3 
Test your ConvNet trained in Task 2 with your own digit writings.

Requirement
a) Inference on your own image using model.predict and then generate the labels
b) Plot your original writing (img) and the resized image (input of the model).
c) Test 10 images which cover 0 - 9.
