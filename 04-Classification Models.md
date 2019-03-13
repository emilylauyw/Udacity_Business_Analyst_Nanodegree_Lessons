# 04 - Classification Models

## Classification Problems
- New class of predictive models: classification models
- These models help identify what group a data point belong to. Example, if we were to decide whether a person qualifies for a loan or not, we need to look at the person's loan application and classify whether the person should be in the approve loan group or the not approve loan group.

### Classification Models Types:

- Logistic Regression
- Decision Trees
- Random Forests
- Boosted Models

### Classification Problems Types

1. Business problems
- Email as spam or inbox?
- Customer going to renew contract or not?

2. Scientific problems
- What land cover type is a pixel from a Satellite image?
- Does soy bean have a disease or not?

3. Real life problems
- What color shirt looks best on me?
- What type of transportation will employee use to go to work?

#### Classification Grouping

1. Binary: equal 2 groups
- One that has a yes or no, a 1 or a 0 or a true or false type of value associated with it.

2. Non-binary: more than 2 groups
- the ones that are categorical meaning there are values that take on names, or labels such as red, green, blue, or small, medium and large.

## Binary Classification Problems

### Building out binary classification models
1. Logistic Regression
- Most basic forms of regression modeling
- Formula is very similar to that of a linear regression

![Linear](Screenshots/06.png "Linear Regression")

![Logistic](Screenshots/07.png "Logistic Regression")

#### Logistic regression algorithms
- Logit transformation equation
  - Focus on concepts
  - How to apply them
  - How to interpret results

- Probit transformation equation
- Log-Log transformation

![Algorithms](Screenshots/08.png "Algorithms")

#### Stepwise regression
- Way to automatically identify which variables are most important to the model and only include them in the model
- Focus on concepts
- Work for Logistic and linear regression
- A process where variable are added and/or removed until the best combination of variables is identified

#### Validating Models
- Validate model against an independent datasets
- What is the overall accuracy of the model?

2. Decision Trees
- Analyzes data as if they were a series of decisions.

#### Root Node Error
- A percentage of how many of the data points went to the incorrect terminal node (predicted incorrectly) when all of the data points are validated against themselves within the entire training set (the Estimation dataset).

![Root Node Error](Screenshots/09.jpg "Root Node Error")

#### Pruning Table
- Lists out the levels in the decision tree with their related error terms with cross-validation samples.

![Pruning Table](Screenshots/10.jpg "Pruning Table")

#### Confusion Matrix
- A matrix (or table) that lists out all of the possible prediction results when we validate our model against our validation set. This confusion matrix is one of the best methods to review the accuracy and precision of your model as well as to understand any model bias in classifying your data points.

![Confusion Matrix](Screenshots/11.png "Confusion Matrix")

#### Variable Importance Plot
- indicate the importance of the variable

![Variable Importance Plot](Screenshots/12.png "Variable Importance Plot")

#### Scoring the model
- Means when we put a model into productions

## Binary Classification Problems

### 3 Types of Models:
1. Decision Trees
- Decision Trees are prone to an error called over fitting, where the model fits the sample data too well, and as a result, does not predict future results as well as it should.

- A technique that helps to eliminate this issues is the Random Forest Model.

2. Forest Models
-
3. Boosted Models
-
