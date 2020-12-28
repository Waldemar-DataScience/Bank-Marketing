# Portfolio Project 1 - Classification

## Bank Marketing

### General Overview
The business aim of the project is to increase efficiency of bank marketing campaign offering a bank deposit to the clients.
We took historic data describing results of previous campaigns and create a Machine Learning binary classification model predicting if the client is likely to accept the offer. Such a model can reduce the cost of campaign - we can more efficiently choose the client to contact and increase the number of bank deposits. 

### Data Used
I used the public available data stets available to 
UCI Machine Learning Repository, Bank Marketing Data Set
[link here](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing#)

Citation: 

 [Moro et al., 2011] S. Moro, R. Laureano and P. Cortez. Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology. 
  In P. Novais et al. (Eds.), Proceedings of the European Simulation and Modelling Conference - ESM'2011, pp. 117-121, Guimarães, Portugal, October, 2011. EUROSIS.

  Available at: 
  
  [pdf] http://hdl.handle.net/1822/14838
  
 [bib] http://www3.dsi.uminho.pt/pcortez/bib/2011-esm-1.txt



### Project contents

The project contains two notebooks EDA1 and EDA2 where data preparation is done. I prepared some Exploratory Data Analysis containing:
1. Descriptive statistics
2. Outliers removal
3. Feature selection.

Since project contains both categorical and numerical data the standardisation and transformation data from categories into numeric values was done.

The third file ML training contains comparison of different classification algorithms. The optimisation within an algorithm also was made.

### Algorithms used


1. K Nearest Neighbours
2. Naive Bayes
3. Support Vector Machine
4. Logistic Regression
5. Decision Tree
6. Random Forest


### Summary

The Decision Tree was most effective algorithm with 92,7% accuracy.



Future improvements are planned. Some are marked in TODO comments, also I am going to add new algorithms.

*This is version 0.9 from 28 December 2020.*


