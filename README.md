# Module 12 Report Template

## Overview of the Analysis

This challenge consists of the following subsections:

    *Split the Data into Training and Testing Sets
    *Create a Logistic Regression Model with the Original Data
    *Predict a Logistic Regression Model with Resampled Training Data

A value of `0` in the “loan_status” column means that the loan is healthy. A value of `1` means that the loan has a high risk of defaulting.

## Results

* Machine Learning Model 1:
the precision (pre) is at 100% for healthy and 85% for high risk loans with 99% recal for healthy and 91% for unhealthy loans


* Machine Learning Model 2:
The precision was 100% for healthy and 84% accuracy for unhealthy lonns but the recall was improved for the risky loans (91% VS 99%)
## Summary

The logistic regression model, fit with oversampled data has a very similar result to prev case (100% and 84%) but the recall was improved for the risky loans (91% VS 99%)