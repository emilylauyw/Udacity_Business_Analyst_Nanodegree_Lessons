# 07 - Segmentation and Clustering

## Segmentation Fundamentals

### Standardization
- Treat all of the objects in the same way
- cheapest and most efficient approach

### Localization
- Allows you to customize based on specifics of the individual.

### Clustering
- A mathematical procedure for multidimensional analysis. Given the characteristics of a set of objects, this procedure groups similar objects into clusters.
- Clustering algorithms try to create segments so that the objects within each segment are as similar or close to each other as possible.
- Learn from multiple variables supplied in the data. It then groups the objects without being told the logic by which to do it. After this process, it ends up creating a new variable known as the cluster number.

#### Distance
- A way to quantify or measure similarity

#### Learning models
- Supervised: modeling process learns from the target (e.g. various predictive methods such as linear or logistic regression with predictor variables and target variable).
- Unsupervised: No target variable that is used in creating the model. (e.g. clustering)

## Preparing Data for Clustering

### Searching for the right data
- Understanding the objective for the segmentation you are trying to create

### Categorical Data
- The statistical data type consisting of categorical variables or of data that has been converted into that form.

### Scaling or Standardizing the data
- Impt to consider when getting data ready for a clustering process
- Since the distance concept is important to determining clusters, the relative size of the values between the variables used become important as well.

### Z-Score (standard score)
- Measures the number of standard deviations each value is from the mean

## Variable Reduction
- Account for the most of the variance in all of the observed variables.

## Clustering models

### Hierarchial
- Determining the closest distance between entities.
- Works better on a small set of objects and can be slow with a larger set of objects due to the large number of merge or split decisions that it makes.

### K-Centroid
- Finding the objects that are closest to the centroid.
- Works well with a larger set of objects and tends to be more efficient in creating the clustering solution.
- Works well with rounded sets of data or where the clusters are equal sizes in densities.



## Validating and Applying Clusters
