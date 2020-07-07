# Multivariate Linear-Regression-No-librarires-
Implementation of linear regression (works for _multivariate data_) from scratch in python without any libraries

This implementation is running and tested on 2 mini datasets for other datasets few modifications might be required. 
<br/><br/>
**Dataset 1** is of some chain of fast food restaurant and has only two attributes namely the population of the city (in 10,000s) in which the restaurant is located and the annual profit made by the restaurant (Profit in $10,000s). Suppose the owner of the chain is considering different cities for opening a new restaurant. The idea is to help the owner, who is considering different cities for opening a new restaurant, in predicting the profits given the population of city 
</br><br/>
**Dataset 2** is about housing prices and contains the size of the house (in square feet), the number of bedrooms, and the price of the house (in $). The idea is to help buyers and sellers to predict the price of their houses.

# How to run
All the python code is present in well formatted google colab notebook in the repository, barely few clicks are needed to re run the whole algorithm from training to testing. Dataset will be download automatically by running the cell 
<br/><br/>
Implementation includes 
- Data Normalization 
- Linear Regression 
  - line fit
  - cost function 
  - gradient decent 
  - auto training stop if convergence differnece for two consecutive itterations is less than 0.001 
- Cost vs Itterations plot 
- Line of best fit 
- 3d plot for multivariate function 
