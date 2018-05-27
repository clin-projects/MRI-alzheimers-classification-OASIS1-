# Predict dementia stage using MRI images of the brain

**Summary**

We use a neural network to predict dementia stage, based on:
- brain volume relative to head size (a feature extracted from MRI images)
- gender
- education level

Prediction of ~60% on the test set

Only rationale for NN architecture was to keep it relatively simple. The learning rate of optimizer was lowered because it was initially learning too quickly (accuracy curve was too steep).

Also, before doing the modeling bit, we performed a simple exploratory data analysis.

**Future work**

An interesting project would be to perform a full-blown CNN on the raw data.

An interesting one-off project would be to look at the longitudinal dataset to predict whether a patient who does not have dementia now, will develop it in the future

**Data**

Data is from the [OASIS1 dataset](http://www.oasis-brains.org/#oasis1). It can also be obtained from [Kaggle](https://www.kaggle.com/jboysen/mri-and-alzheimers).
