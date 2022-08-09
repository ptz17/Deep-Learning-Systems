# Task 1: Binary classification 
Input dataset: dataset-1.csv
Features: first 4 columns
Label.  : last column


Task 1-1: Model-1 to implement
1 hidden layer without activation function
Model parameter: 4(input dim) -> N (hidden: define by yourself) -> 1 (output) + sigmoid


Task 1-2: Model-1 to implement
1 hidden layer with sigmoid as activation function
Model parameter: 4(input dim) -> N (hidden: define by yourself) -> sigmoid -> 1 (output) + sigmoid

    
Requirements
1) define 4 seperate functions for forward(), backward(), binary_crossEntropy(), and evaluation()
2) Use 80% (i.e., 80 data points to train), 20% (i.e., 20) for testing
3) Adjust your learning rate and number of training iterations (epochs) and print out
       a) loss function, b) accuracy (training and testing), and c) number of iteration
       for example: "epoch 1: loss = 999.00, train acc = 0.10, test acc = 0.01"
4) your batch size should be 1 - 80 
5) allowed package: numpy 
6) Loss function: Binary Cross Entropy

# Task 2: Regression for fix-point binary numbers 
Input dataset: random numbers

Model: Design model as you need

Dataset generation requirements:
1) Data format : X7 X6 X5 X4 . X3 X2 X1 X0  = 2^3*X7+2^2*X6+2^1*X5+2^0*X4 . (2^3*X3+2+2^2*X2+2^1*X1+2^0*X0)/2^4
2) X_i is Boolean
3) For example, X = {10101000}, i.e., 1010.1000 = 10.5;   (10 + 8/16)
                X = {00010010}, i.e., 0001.0010 = 1.125;  (1 + 2/16)

Requirements
1) define 4 seperate functions for forward(), backward(), binary_crossEntropy(), and evaluation()
2) Use 50% of the data for training and 50% for testing (note: total number of data points is fixed)
3) Adjust your learning rate and number of training iterations (epochs) and print out
       a) loss function training and b) testing
       for example: "epoch 1: train mse = 0.10, test mse = 0.01"
5) allowed package: numpy 
6) use MSE as loss function
