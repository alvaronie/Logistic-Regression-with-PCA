# Logistic-Regression-with-PCA
The objective is to create a predictive classification model using Logistic Regression and to discuss the implementation of Principal Component Analysis (PCA).
### Iintroduction to PCA

Principal Component Analysis (PCA) is a dimensionality reduction technique that can be used to reduce a larger set of feature variables into a smaller set that still contains most of the variance in the larger set.

Preserve the variance
PCA, first identifies the hyperplane that lies closest to the data and then it projects the data onto it. Before, we can project the training set onto a lower-dimensional hyperplane, we need to select the right hyperplane. The projection can be done in such a way so as to preserve the maximum variance. This is the idea behind PCA.

Principal Components
PCA identifies the axes that accounts for the maximum amount of cumulative sum of variance in the training set. These are called Principal Components. PCA assumes that the dataset is centered around the origin. Scikit-Learn’s PCA classes take care of centering the data automatically.

Projecting down to d Dimensions
Once, we have identified all the principal components, we can reduce the dimensionality of the dataset down to d dimensions by projecting it onto the hyperplane defined by the first d principal components. This ensures that the projection will preserve as much variance as possible.


### Data set

The data set was found on the web: https://archive.ics.uci.edu/dataset/2/adult. And its extraction was done following the commands posted on the website itself.In this data set the prediction task is to determine whether a person makes over 50K a year.
