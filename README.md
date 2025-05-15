# Machine-learning-methods-for-forest-type-classification
Machine learning methods were used to classify land plots into different classes using Random Forest, SVM, and neural networks. Clustering analysis with Iterative Distance-Based, EM Mixture Model, and DBSCAN was performed to identify homogeneous data groups.
## Overview
During this project, analyses were conducted on data referring to four land areas located in the Roosevelt National Forest in northern Colorado (USA). The main goal was to classify each individual observation based on the type of vegetation present, i.e., to determine which of the seven forest types each instance belongs to. The analysis was carried out by training machine learning algorithms that, using the explanatory variables available in the dataset, are able to assign each observation to its corresponding forest type.

A secondary objective was to apply unsupervised algorithms capable of identifying homogeneous groups within the data that are heterogeneous between them. The purpose of this investigation was to detect clusters where the analyzed land plots are geographically close to one another—meaning they belong to one of the four wilderness areas into which the Roosevelt National Forest is divided.

## Materials

The dataset comes from the United States Geological Survey (USGS) and the United States Forest Service (USFS), and it refers to four wilderness areas located in the Roosevelt National Forest in northern Colorado. These areas are considered wilderness because they are not affected by human activity, and the forest types found within them result from natural ecological processes rather than forest management practices.

The original dataset contains 581012 observations, but the dataset used in this analysis is a reduced version, selected from a Kaggle competition. It includes 15120 observations and 54 variables: 10 quantitative variables, 4 binary variables representing the types of wilderness areas, and 40 binary variables for soil types. Each observation corresponds to a 30m x 30m forest land plot. The objective of the analysis is to classify each land plot according to its forest type.
