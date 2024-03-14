# Fraud Detection with Deep Learning

This project aims to predict fraudulent transactions in credit card data using deep learning techniques. The steps for this project are outlined in the following sections:
### Exploratory Data Analysis using Pandas

* Gather data using read_csv
* Explore the data using pandas library
* Preprocess the data for use in a neural network model.
* Compile and evaluate a binary classification model using a neural network.
* Optimize the neural network model.

### Prepare the Data for Use in a Neural Network Model

We begin by preprocessing the credit card transaction dataset so that it can be utilized to compile and evaluate the neural network model later. some of the following data preparation steps are:
1. Read the credit card transaction data into a Pandas DataFrame.

2. Review the DataFrame for any categorical variables that will require encoding, as well as columns that will define the features and target variables.

3. Create the features (`X`) and target (`y`) datasets using the preprocessed data.

4. Split the features and target sets into training and testing datasets.

5. Scale the features data using scikit-learn's StandardScaler.

### Compile and Evaluate a Binary Classification Model Using a Neural Network

Designing a binary classification deep neural network model that predicts fraudulent transactions based on the credit card dataset's features. Compile and fit the model, and evaluate it to calculate the model’s loss and accuracy by:

1. Creating a deep neural network specifying the number of input features, layers, and neurons using TensorFlow’s Keras.

2. Compile and fit the model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric.

3. Evaluate the model using the test data to determine the model’s loss and accuracy.

### Optimize the Neural Network Model

Optimize the initial neural network to define two new models (including the original), and try to enhance each model’s predictive accuracy. 

displaying the accuracy scores achieved by each model and compare the results.
