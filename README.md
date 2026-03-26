# Developing a Neural Network Regression Model

## AIM
To develop a neural network regression model for the given dataset.

## THEORY
The objective of this experiment is to design, implement, and evaluate a Deep Learning–based Neural Network regression model to predict a continuous output variable from a given set of input features.

In many real-world applications—such as house price prediction, temperature forecasting, sales estimation, or demand prediction—the relationship between input variables and the output is non-linear and complex. Traditional statistical models often fail to capture these patterns effectively. Deep Learning models, particularly Artificial Neural Networks (ANNs), are capable of learning such complex relationships through multiple hidden layers and non-linear activation functions.

In this experiment, a dataset containing multiple independent variables (features) and a dependent variable (target) is provided. The task is to preprocess the data, construct a neural network regression architecture, train the model using backpropagation and gradient descent, and evaluate its performance using appropriate regression metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R² score.

The experiment aims to understand how network architecture, learning rate, number of epochs, and activation functions affect the accuracy of regression predictions and to demonstrate the effectiveness of deep learning in solving regression problems.

## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 

Create your dataset in a Google sheet with one numeric input and one numeric output.

### STEP 2: 

Split the dataset into training and testing

### STEP 3: 

Create MinMaxScalar objects ,fit the model and transform the data.

### STEP 4: 

Build the Neural Network Model and compile the model.

### STEP 5: 

Train the model with the training data.

### STEP 6: 

Plot the performance plot

### STEP 7: 

Evaluate the model with the testing data.

### STEP 8: 

Use the trained model to predict  for a new input value .

## PROGRAM

### Name:

### Register Number:

```python
class NeuralNet(nn.Module):
    def __init__(self):
        super().__init__()
        #Include your code here



# Initialize the Model, Loss Function, and Optimizer



def train_model(ai_brain, X_train, y_train, criterion, optimizer, epochs=2000):
    #Include your code here

```

### Dataset Information
Include screenshot of the generated data

### OUTPUT

### Training Loss Vs Iteration Plot
Include your plot here

### New Sample Data Prediction
Include your sample input and output here

## RESULT
Thus, a neural network regression model was successfully developed and trained using PyTorch.
