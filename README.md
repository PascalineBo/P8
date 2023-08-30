# Machine Learning initiation

## Notebook describing a dataset Principal Component Analysis, followed by a model training using Sci-kit-learn and an unsupervised analysis using K-means

## Analysis' language: Python (in Jupyter Notebook)

### Context: using a dataset of 26 196 real estate transactions in Paris, between 2017 and 2021, give an estimate of a real estate portfolio comprised of 175 assets

#### Notebook's structure:

#### Milestone 1 : Data Analysis:

- Observation of the data types, data use of space. Corrections and data cleaning. 
- Search of existing correlations between data dimensions
  
#### Milestone 2 : Algorithm training

- Use of a linear regression algorithm.
- The algorithm is trained to predict the m2 of an estate given its type (business or private), neighbourhood (zip code), day of the estimate
- 33% of the dataset is kept for testing
- Accuracy of the model on test data: 94,76%.

#### Milestone 3 : Prediction for the Customer

- trimming of customer's file to fit with the model
- customer's portfolio value estimate, using the model and based on customer's portfolio data

#### Milestone 4 : test dataset classification - unsupervised analysis

- automatic classification of real estate assets between business and private
- use of K-means algorithm
