# Wine_pred
Wine Prediction System using Deep Learning

**Overview**
The Wine Prediction System is a deep learning application designed to classify wines based on their chemical properties. Utilizing a neural network built with Keras, this system predicts the type of wine (red or white) from its features.

**DATASET:**
1. RED dataset: http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv
2. WHITE dataset: http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv

**Features**
1. Binary Classification: Predicts whether a wine is red or white.
2. Deep Learning Model: Utilizes a neural network with multiple layers and activation functions.
3. Reproducibility: Ensures consistent results through the use of a fixed random state.

About the Data Set : Before we start loading in the data, it is really important to know about your data. The data set consist of 12 variables that are included in the data. Few of them are as follows –
1. Fixed acidity : The total acidity is divided into two groups: the volatile acids and the nonvolatile or fixed acids.The value of this variable is represented by in gm/dm3 in the data sets.
2. Volatile acidity: The volatile acidity is a process of wine turning into vinegar. In this data sets, the volatile acidity is expressed in gm/dm3.
3. Citric acid : Citric acid is one of the fixed acids in wines. It’s expressed in g/dm3 in the data sets.
4. Residual Sugar : Residual Sugar is the sugar remaining after fermentation stops, or is stopped. It’s expressed in g/dm3 in the data set.
5. Chlorides : It can be a important contributor to saltiness in wine. The value of this variable is represented by in gm/dm3 in the data sets.
6. Free sulfur dioxide : It is the part of the sulfur dioxide that is added to a wine. The value of this variable is represented by in gm/dm3 in the data sets.
7. Total Sulfur Dioxide : It is the sum of the bound and the free sulfur dioxide.The value of this variable is represented by in gm/dm3 in the data sets.

**Installation**
To run the Wine Prediction System, you need to have Python installed along with the following libraries:
1. Pandas
2. NumPy
3. scikit-learn
4. TensorFlow (which includes Keras)

**Model Details**
1. Layer 1: Dense layer with 12 neurons and ReLU activation function.
2. Layer 2: Dense layer with 9 neurons and ReLU activation function.
3. Output Layer: Dense layer with 1 neuron and sigmoid activation function.
4. The model uses binary cross-entropy as the loss function and the Adam optimizer for training.

**Results**
After training, the model's performance can be evaluated using the test set. Typical metrics include loss and accuracy.
