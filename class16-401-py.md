# Machine Learning Introduction
Machine learning: Machine learning is the practice of teaching computers how to learn patterns from data, often for making decisions or predictions.

## Algorithm
Machine learning is a comprehensive approach to solving problems, 
and individual algorithms are only one piece of the puzzle. The rest of the puzzle is how you apply them the right way.

## Top Terminologies
-Model - a set of patterns learned from data.
- Algorithm: a specific ML process used to train a model.
- Training data: the dataset from which the algorithm learns the model.
- Test data: a new dataset for reliably evaluating model performance.
- Features: Variables (columns) in the dataset used to train the model.
- Target variable: A specific variable you're trying to predict.
- Observations: Data points (rows) in the dataset.

## The 3 Elements of Great Machine Learning
1. human guidance
2. clean, relevant data
3. avoid overfitting (the machine memorize the data instead of using it to create a model)

## dataset
- You’ll gain valuable hints for Data Cleaning (which can make or break your models).
- You’ll think of ideas for Feature Engineering (which can take your models from good to great).
- You’ll get a "feel" for the dataset, which will help you communicate results and deliver greater impact.

> Categorical features cannot be visualized through histograms. Instead, you can use bar plots.

**Handle Missing Data**: 
1. Dropping observations that have missing values
2. Imputing the missing values based on other observations

## Feature Engineering
**creating new input features from your existing ones.**

**but why?**
1. You can isolate and highlight key information, which helps your algorithms "focus" on what’s important.
2. You can bring in your own domain expertise.
3. Most importantly, once you understand the "vocabulary" of feature engineering, you can bring in other people’s domain expertise!
4. Create Interaction Features

## Algorithm Selection

**linear regression suffers from two main flaws:**
1. It's prone to overfit with many input features.
2. It cannot easily express non-linear relationships.

**to solve overfit**
> Regularization is a technique used to prevent overfitting by artificially penalizing model coefficients.
- Lasso Regression (Least Absolute Shrinkage and Selection Operator.) (penalizes the absolute size of coefficients.)
- Ridge Regression (penalizes the squared size of coefficients.)
- Elastic-Net (mix of both absolute and squared size.)

**to solve non-linearity**
Tree Ensembles
- Bagging
> Bagging attempts to reduce the chance overfitting complex models
- Boosting
> Boosting attempts to improve the predictive flexibility of simple models.


## Model Training
1. Split Dataset (train / test)
2. Cross-Validation
3. Fit and Tune Models
4. Select Winning Model
> performance metrics:
> 1. For regression tasks, we recommend Mean Squared Error (MSE) or Mean Absolute Error (MAE). (Lower values are better)
> 2. For classification tasks, we recommend Area Under ROC Curve (AUROC). (Higher values are better)






