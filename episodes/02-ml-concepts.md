---
title: "Machine learning concepts for geospatial data"
teaching: 10 # teaching time in minutes
exercises: 2 # exercise time in minutes
---

:::::::::::::::::::::::::::::::::::::: questions

- What is machine learning and how is it used for geospatial data analysis?
- What is the difference between supervised and unsupervised learning?
- What is the difference between machine learning and deep learning?
- When should you use machine learning for geospatial data analysis?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Explain machine learning concepts for geospatial data
- Describe difference between supervised and unsupervised learning
- Describe the difference between regression, classification and clustering tasks
- Describe the difference between machine learning and deep learning
- Explain the usefulness of machine learning for geospatial data analysis

::::::::::::::::::::::::::::::::::::::::::::::::

## Machine learning

In data analysis, we often define a mathematical algorithm to show the
relationship between a set of input variables and an output variable. This is
called a model. In mathematical notation, the predicted value $\hat{y}$ can be
written as:

$\hat{y}(w, x) = w_0 + w_1 x_1 + \dots + w_n x_n$

Where $w$ are the model parameters, $x$ are the input variables. We can adjust
the model parameters $w$ to improve how well the model can produce the output
variable from the input variables. Therefore, we are interested in the
difference between the predicted value $\hat{y}$ and the true value $y$. This is
called the "error", and we can write its magnitude as:

$e = |y - \hat{y}|$

The process of adjusting the model parameters to minimize the error is called
"training" the model. One way to do this is to use a lot of samples of input and
output data, and use an "optimization" algorithm to find the best model
parameters that minimize the error. This is called "fitting" the model to the
data. In other words, the model "learns" from the data by adjusting its
parameters to minimize the error. When we find the best model parameters that
minimize the error, we can use the model to make predictions (or inferences) on
new data.

The whole process of training a model, defining optimization algorithms, and
using the model to make predictions is called [machine learning
(ML)](https://en.wikipedia.org/wiki/Machine_learning) and it is a subset of
artificial intelligence (AI): all machine learning is AI, but not all AI is
machine learning.

Geospatial ML is the application of machine learning techniques to data with a
spatial and spatio-temporal components.

Machine learning is a powerful tool for geospatial analytics because it can
leverage large amounts of spatial data, time series data, satellite and aerial
imagery, or any other form of geographic information to do tasks such as
predictions, classification, or identifying patterns in the data. The
application of machine learning to geospatial data is vast; for example,
predicting the spread of wildfires, classifying land cover types, or identifying
areas at risk of flooding.


::::::::::::::::::::::::::::::::::::: keypoints


::::::::::::::::::::::::::::::::::::::::::::::::
