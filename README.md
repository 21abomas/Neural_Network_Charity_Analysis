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
