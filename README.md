# Using-Python-for-Research
HarvardX's PH526X

This repository contains code used in the Using Python for Research course on HarvardX. This course seeks to bridge introductory Python courses with the use of Python in scientific computing by introducing modules like Numpy, Pandas, Matplotlib, and Scikit-Learn and using them in case studies. The course is broken up across five weeks, with ten homework assignments and a final project. The topics are as follows:

1. Week 1: Basics of Python 3
2. Week 2: Python Libraries and Concepts Used in Research
3. Week 3: Case Studies Part 1: DNA Translation, Language Processing, and Classification
4. Week 4: Case Studies Part 2: Whisky Classification, Bird Migration, and Social Network Analysis
5. Week 5: Statistical Learning: Linear and Logistic Regression, Random Forest

This repo includes code for all homework assignments and for the case studies written in class, as well as the corresponding data. It additionally contains a submission for the final project, in which the student was tasked with predicting physical activity based on a dataset of x, y, and z accelerations and corresponding training set labels. 10-fold cross-validation and a parameter search using a random forest classifier was used for the final model. All assignments are in the form of Jupyter notebooks. The following summarizes the topics covered by each .ipynb file:

HW 1: Counting letter frequencies in text, approximating pi using random sampling, smoothing via nearest-neighbor averaging  
HW 2: Making a working tic-tac-toe game with random and semi-strategic AI  
Case Study 1: DNA translation- downloading nucleotide sequences from NCBI and using an amino acid translation table to predict the resulting AA sequence  
HW 3-1: Implementing a Caesar cipher  
Case Study 2: Language processing- analyzing word frequency statistics in texts from different languages  
HW 3-2: Comparing word frequency statistics in different translations of Hamlet  
Case Study 3: Introduction to kNN classification- implementing a homemade kNN classifier  
HW 3-3: Analyzing wine quality using sklearn preprocessing, PCA, and comparing the homemade kNN classifier to scikit-learn's  
Case Study 4: Classifying whiskies using Pandas DataFrames- exploring correlations and spectral co-clustering  
HW 4-1: Examining whisky flavor profiles by region and using bokeh for interactive visualization  
Case Study 5: GPS Tracking of Birds- examining flight speed, datetime, daily mean speed, and the cartopy library  
HW 4-2: Grouping using groupby() in Pandas to find mean speeds and altitudes per bird and date  
Case Study 6: Social network analysis- NetworkX package for visualizing and manipulating graph structures, generating random graphs, analyzing degree distribution, and calculating largest connected component  
HW 4-3: Analyzing graph homophily by calculating marginal probabilities of a characteristics, chance homophily, and true homophily of sex, caste, and religion of two villages  
HW 5-1 and 5-2: Analyzing the TMDb dataset to predict revenue using linear regression and random forest regressors and whether a movie will be profitable (revenue > budget) using logistic regression and random forest classifiers in scikit-learn  
Final project: Using scikit-learn to predict physical activity based on accelerometer data
