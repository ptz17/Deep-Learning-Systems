# Build fixpoint calculator using LSTM Networks
Task Summary: Train a LSTM Network to perform 20-bit fix-point addition  


# Task 1
Dataset preparation (format)  \
Let's use [19:10]_2.[9:0]_2 as the UN-SIGNED fix-point representation \
   for example, 01000.10000 = 2^3.5 = 8.5 \

Requirement \
1) Need to have seperate functions, including (check out bracket-2 in lab3-demo)
   1-a) data generation
   1-b) data conversion and inversion (inversion for inference/testing use)


# Task 2
Build and Train a TWO-LAYER LSTM Network (two stacked LSTM). \
1) Feel free to use any optimizers, normlization techniques, decaying, etc., techniques 
2) Your training dataset should be LESS THAN 50% of the total data points 
3) In the testing phase, you should implement (check out bracekt-8 in lab3-demo) 
 3-a) Inference with accuracy as metrics 
 3-b) Inference with MSE as metrics 
 3-c) Showing at least 50 cases (individual inference) 


# Task 3
Re-do Task 2 by replacing all LSTM layers with GRU and summarize your observations in prediction performance and computation efficiency. 
Must use the same optimizer, learning rate, and number of training epochs as used in Task 2. 