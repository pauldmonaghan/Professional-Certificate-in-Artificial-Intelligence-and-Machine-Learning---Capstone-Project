# Model Card

## Model Description

**Input:** Describe the inputs of your model

Function 1: Grid points in a square area
Function 2: Noisy data
Function 3: Drug/human attributes
Function 4: Metrics relating to online sales
Function 5: Metrics pertaining to possible chemicals to use in a chemical reaction
Function 6: Rating statistics pertaining to flavor, consistency, calories, waste and cost of cakes
Function 7: Data to used alongside 6 Hyperparameters of a popular and frequently used machine learning model
Function 8: Data to used alongside 8 Hyperparameters of an unknown machine learning model

**Output:** Describe the output(s) of your model

Function 1: Sources of radiation
Function 2: Unknown machine learning model
Function 3: Effect on a given human
Function 4: Number of online sales
Function 5: Yield statistics based on given chemical combinations reacting with each other
Function 6: Overall cake score
Function 7: Machine learning model performance
Function 8: Machine learning model performance

**Model Architecture:** Describe the model architecture you’ve used

## Performance

My model performed best for function 4, in part due to it having many local optima, making it more likely to find these optima via random search. The latest observation of this function via this method was 0.25

## Limitations

The random search aspect of my model is only as precise as the variance assigned to it (ie, how limited its search radius is by a user).

## Trade-offs

The grid search aspect of the Bayesian Optimisation is very slow for a large number of hyperparameters when using the nested for loop method to form the grid with a large number of grid points. Reducing the number of grid points improves performance, but at the cost of accuracy of the solutions obtained.