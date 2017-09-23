## Project: Predicting Boston Housing Prices


### Summary
- Use NumPy to investigate the latent features of a dataset.
- Analyze various learning performance plots for variance and bias.
- Determine the best-guess model for predictions from unseen data.
- Evaluate a model's performance on unseen data using previous data.

### Code

This project contains three files:

- `boston_housing.ipynb`: main file for analysis.
- `housing.csv`: The project dataset. 
- `visuals.py`: supplementary visualizations 


### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes

### Requirement

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)