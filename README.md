## Feature selection for multiple linear regression using Scikit-learn

We'll work with a dataset on sold houses in Ames, Iowa. Each row in the dataset describes the properties of a single house as well as the amount it was sold for. In this course, we'll build models that predict the final sale price from its other attributes. Specifically, we'll explore the following questions:

* Which properties of a house most affect the final sale price?
* How effectively can we predict the sale price from just its properties?
* Dataset can be downloaded [here](https://ww2.amstat.org/publications/jse/v19n3/decock/AmesHousing.txt)

Here are some the columns in dataset:
* `Lot Area`: Lot size in square feet.
* `Overall Qual`: Rates the overall material and finish of the house.
* `Overall Cond`: Rates the overall condition of the house.
* `Year Built`: Original construction date.
* `Low Qual Fin SF`: Low quality finished square feet (all floors).
* `Full Bath`: Full bathrooms above grade.
* `Fireplaces`: Number of fireplaces.

The code is in two seperate parts. In the first part, I have written three seperate functions as follows:

* `transform_features()` : transforms features in the dataset to something meaningful for analysis
* `select_features()` : feature selection happens here
* `train_and_test()` : we will train and test our model and this function reports the final rmse of the model.

Second part summarizes how I came up with the way these functions are and have provided a backup calculation for the rational of these functions.
