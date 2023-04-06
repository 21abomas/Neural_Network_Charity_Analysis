# Neural_Network_Charity_Analysis
## Alphabet Soup Charity Analysis

### Overview
This project aims to examine and classify the success of charitable donations using deep-learning neural networks and the TensorFlow framework in Python. For the analysis, we preprocess the data for the neural network model, then compile, train, evaluate the model and optimize the model.. The project is divided into three deliverables:


### Preprocessing Data for a Neural Network Model

The first step in this project is to preprocess the dataset in order to compile, train, and evaluate the neural network model later in Deliverable 2. The following steps are performed in the AlphabetSoupCharity.ipynb file:

* Read in the charity_data.csv to a Pandas DataFrame.
* Identify the target(s) and feature(s) for the model and drop the EIN and NAME columns.
* Determine the number of unique values for each column, and for those columns that have more than 10 unique values, determine the number of data points for each unique value.
* Create a density plot to determine the distribution of the column values, and use the plot to create a cutoff point to bin "rare" categorical variables together in a new column, Other.
* Generate a list of categorical variables and encode them using one-hot encoding.
* Merge the one-hot encoding DataFrame with the original DataFrame, and drop the originals.
* Standardize numerical variables using Scikit-Learn’s StandardScaler class, then scale the data.

### Compile, Train, and Evaluate the Model

Using the preprocessed data from Deliverable 1, a neural network is designed to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. The following steps are performed in the AlphabetSoupCharity.ipynb file:

* Create a neural network model by assigning the number of input features and nodes for each layer using Tensorflow Keras,
* Create the first hidden layer and choose an appropriate activation function,
* Compile and train the model,
* Create a callback that saves the model's weights every 5 epochs,
* Evaluate the model using the test data to determine the loss and accuracy and finally
* Save and export the results to an HDF5 file, and name it AlphabetSoupCharity.h5.

### Optimize the Model

In Deliverable 3, the goal is to optimize the model to achieve an accuracy greater than 75%. 
unfortunatly This model was unable to achieve the aim of 75% accuracy and did not appear to respond to modifications.Overall, implementing a combination of PCA, other models, and feature engineering techniques can help to improve the accuracy of the current model and make more accurate predictions
