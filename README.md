![Credit Card Fraud Detection]()
# Prediction of Credit Card Fraudulent Transaction Using Supervised Machine Learning Techniques
We obtained the Credit Card Fraudulent Transaction dataset from Kaggle website and used Jupyter Notebook as the platform for the purpose of coding. Our methodology involves use of Outlier finding techniques like Local Outlier Factor and Isolation Forest Algorithm.
## A. Feature Selection
Feature selection is finding the subset of original features by different approaches based on the information they provide, accuracy, prediction errors.
The features used in the project are Dimensionally reduces in given dataset using PCA:
- V1 
- V2 <br />
...
- V28
## B. Model Selection
* Local Outlier Factor
* Isolation Forest
## C. Training the models with Data
The data taken is from **https://www.kaggle.com/mlg-ulb/creditcardfraud**
### Then the Outliers are predicted:
- 0 if Non-fraudulent Transaction
- 1 if Fraudulent Transaction
# Result =>
- Local Outlier Factor has accuracy of nearly 98.1%
- Isolation Forest has accuracy of nearly 98.3%
But, accuracy is not a correct measure here because the amount of Fraudulent Transactions are very less in the dataset. So, even if we mark all transactions tobe non-fraudulent, algorithms will have high accuracy.
Recall for isolation forest algorithm is much higher than for local outlier factor.
Precision for isolation forest algorithm is also higher than for local outlier factor but its really low if taken individually. 
## Files included in repository are:
- **source.ipynb(Jupyter Notebook-https://jupyter.org/)**
- **source.pdf(Just a pdf print of jupyter notebook)**
<br />

***In source.ipynb, data is visualized using Histograms and Heat Plots Using Correlation Matrices.***
