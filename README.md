# Introduction
In this case study we will be analyzing Employee Attrition Data and will try to build a binary classifier using keras, We will be using the IBM HR Analytics Employee Attrition & Performance Dataset published on [Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset).

In the accompanying notebook : 
1. Setup
2. Exploratory Data Analysis of major factors leading to emplyee attrition
   * Descriptive Statistics
   * Correlation Analysis
3. Preprocessing
   * One-Hot Encoding of Categorical features
   * Split into train/test/validation 
   * Scale the numerical features
4. Binary Classification with keras and imbalanced classes
   * Using class weight
   * Using output neuron initial bias
   * Oversampling
5. Conclusion 
   * Comparing all three methods in terms of weighted average of f1-score, recall and precision. 

