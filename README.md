# part-1-neural-network-analysis
BITSOM Assignment 5\
  Neural Network Analysis

# Dataset Link
https://drive.google.com/drive/folders/1Aihn49cUYMjCgeCTFBTyprjrgZO3UY6r

# Customer Churn Prediction using ANN
## Project Overview
This project builds an Artificial Neural Network (ANN) to predict customer churn. It helps businesses proactively identify customers likely to cancel their service by analyzing usage behavior and contract details.

## Dataset
The dataset `customer_churn_nn.csv` contains 2,000 records with features such as tenure, monthly charges, support tickets, and region.

## Project Workflow
1. **Data Preprocessing**: Removing IDs, Label Encoding, categorical features, and Standard Scaling.
2. **Model Design**: A deep neural network with ReLU hidden layers and a Sigmoid output layer.
3. **Training**: Using the Adam optimizer and Binary Crossentropy loss for 50 epochs.
4. **Evaluation**: Generating a confusion matrix and classification report to assess performance.


## Observations 
### Task 6: Final Reflection

1. What role do weights and biases play in the model?
Weights determine the importance of input features. Biases help shift activation values and improve learning flexibility. Together, they allow the neural network to learn patterns from data.

2. Why Activation Functions Are required?
Activation functions introduce non-linearity. Without them, neural networks behave like simple linear models and cannot learn complex relationships.
**Examples:**
ReLU
Sigmoid
Tanh

3. What happens when learning rate is too high or too low?
**Learning Rate Too High**
-Training becomes unstable
-Loss may oscillate
-Model may never converge
**Learning Rate Too Low**
-Training becomes very slow
-Model may get stuck
-Requires many epochs

4. Underfitting vs Overfitting
**Underfitting Occurs when:**
-Model is too simple
-Training accuracy is low
-Model cannot learn patterns
**Overfitting Occurs when:**
-Training accuracy is very high
-Testing accuracy is low
-Model memorizes training data

**Signs of overfitting:**
Validation loss increases while training loss decreases
