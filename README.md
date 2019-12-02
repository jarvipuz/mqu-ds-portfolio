ITEC657 Data Science Portfolio 
===

Jan Arvin Lapuz  
Master of Data Science  
Macquarie University  


## Portfolio Topics

This repository contains the portfolio projects for the Data Science course taken on the 2nd term of Academic Year 2019. There are 3 projects under this portfolio:

1. **Analysis of Cycling Data** (Portfolio 1)  
The analysis involves combining and exploring cycling datasets extracted from Strava, an online social network for sports, and GoldenCheetah, an application that provides analytics over cycling data. The combined datasets were analysed to explore the key variables in cycling. We also examined the relationships between the key variables by creating a correlation matrix to see how each combination of variables vary together. We further analysed the data by different cycling workout categories. We also investigated which rides get more 'kudos' and visualised the relationship between distance, stress and speed throuh a multi-axis plot.

2. **Data Driven Prediction Models of Energy Use of Appliances in a Low-energy House** (Portfolio 2)  
This portfolio involves the partial replication of a research paper exploring the relationship between energy consumption of appliances and temperature and humidity on rooms in a house and different weather variables. The paper used various machine learning techniques to create robust models of energy consumption but this notebook focuses on multiple linear regression modelling. This analysis involves some data exploration which were also presented in the research paper and the use of recursive feature elimination during multiple linear regression modelling to examine variable importance. Different model diagnostics were calculated for each iteration of the modelling stage.

3. **Clustering Visualisation** (Portfolio 3)  
This notebook presents one of the basic clustering algorithms, the k-means clustering. A dataset with random numbers and initial centroids were provided. The goal is to find the cluster points by visualising each step of the k-means algorithm. This involves iteratively finding which cluster each data point belongs to and recalculating the cluster centroids. The algorithm stops when very little movement or no movement in the cluster centroids is observed.

**Note:** The three portfolios above were combined as one in **Portfolio.ipynb**.


## Packages Used
* pandas
* numpy
* seaborn
* matplotlib
* datetime
* sklearn


## References
* Data driven prediction models of energy use of appliances in a low-energy house. Luis M. Candanedo, Véronique Feldheim, Dominique Deramaix. Energy and Buildings, Volume 140, 1 April 2017, Pages 81-97, ISSN 0378-7788, http://dx.doi.org/10.1016/j.enbuild.2017.01.083
