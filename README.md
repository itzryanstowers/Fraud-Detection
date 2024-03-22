# Fraud Detection with Deep Learning

This project aims to predict fraudulent transactions in credit card data using deep learning techniques. By predicting fraudulent transactions accurately, we can help financial institutions prevent financial losses and gain trust from customers by protecting their card account. The steps for this project are outlined in the following sections:
### Exploratory Data Analysis using Pandas
We begin by understanding the credit card transaction data using Pandas. This initial Exploration helps us:
* Gather data using read_csv function,
* Explore the data using pandas library,
* Preprocess the data for use in a neural network model,
* Compile and evaluate a binary classification model using a neural network,
* Optimize the neural network model,

### Prepare the Data for Use in a Neural Network Model

When performing any neural network techniques, the data needs to be presented in a specific format. This leads us to the next steps which prepares or preprocess's the data to ensure it is suitable for training and evaluating the model effectively. some of the following data preparation and preprocessing steps are:

1. Read the credit card transaction data into a Pandas DataFrame using the "read_csv" function.

2. Review the DataFrame for any categorical variables that will require encoding, as well as columns that will define the features and target variables.

3. Create the features (`X`) and target (`y`) datasets using the preprocessed data.

4. Split the features and target sets into training and testing datasets.

5. Scale the features data using scikit-learn's StandardScaler.

### Compile and Evaluate a Binary Classification Model Using a Neural Network
we designed a deep neural network specifically suited for a binary classification model (which can have 2 outcomes) that predicts fraudulent transactions based on the credit card dataset's features. This method helps identify patterns that differentiate fraudulent transactions from legitimate ones. To compile and fit the model so we can evaluate it, we need to calculate the model’s loss and accuracy by:

1. Creating a deep neural network specifying the number of input features, layers, and neurons using TensorFlow’s Keras.

2. Compile and fit the model using the binary_crossentropy loss function, the adam optimizer, and the accuracy evaluation metric.

3. Evaluate the model using the test data to determine the model’s loss and accuracy.

### Optimize the Neural Network Model
Now that the model has been performed and tested, we can now then work on limiting the loss and accuracy by fine-tuning its architecture or hyperparameters. You can see here we experiement with different configurations to see if we can enhance the models ability to detect fraud by checking the models performance using a visual representation known as a confusion matrix that shows the number of true positives (correct classification of positive cases), False positives (incorrect classifications of positive cases), true negatives (correct classifications of negative cases), and false negatives (incorrect classifications of negative cases).
In two easy steps we were able to:

1. Optimize the initial neural network to define two new models (including the original), and try to enhance each model’s predictive accuracy. 

2. displaying the accuracy scores achieved by each model and compare the results.
