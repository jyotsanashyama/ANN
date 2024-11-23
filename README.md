# Customer Retention Prediction using Artificial Neural Network (ANN)
# Project Overview
This project predicts whether a customer of a bank will stay or leave the bank based on various parameters, using Artificial Neural Network (ANN). 
This model achieves an accuracy of 86.3%.

# Dataset
The dataset includes some important features that are considered in building this model for customer retention:
1. Geography: Customer's location
2. Credit Score: Numeric score of credit card
3. Gender: Male/Female
4. Age: Age of the customer
5. Tenure: Number of years with the bank
6. Balance: Account balance
7. Number of Products: Number of products purchased by the customer
8. Credit Card: Does the customer have a credit card? (Yes/No)
9. Active Member: Is the customer active? (Yes/No)
10. Estimated Salary: Customer's estimated salary
11. Exited: Target variable indicating if the customer left the bank (0: Stayed, 1: Left)

# Project Workflow
1. Data Preprocessing:
- Encoded categorical data using Label Encoding and One-Hot Encoding.
- Split the data into training and testing datasets.
- Applied feature scaling to normalize data.
   
3. Building the ANN:
- Added an input layer.
- Added two hidden layers with Rectifier Activation Function (ReLU).
- Creted a single neuron output layer with Sigmoid Activation Function for binary output.
   
5. Training the ANN:
- Optimized using backpropagation and gradient descent.
- Evaluated using accuracy and confusion matrix.

# Results
Acuuracy: 86.3%

# Technology used
- Programming Language: Python
- Libraries used:
  - Tensorflow
  - NumPy
  - Pandas
  - Scikit-learn
