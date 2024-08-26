# deep-learning-challenge
# Neural Network Model Report for Alphabet Soup

## Overview

The goal of this analysis was to develop a deep learning model to predict the success of funding applications for Alphabet Soup. The target was to achieve at least 75% accuracy in predicting whether an application would be successful.

## Results

### Data Preprocessing

- **Target Variable:** `IS_SUCCESSFUL` (indicates if an application was successful)
- **Feature Variables:** 
  - `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`, `ORGANIZATION`, `STATUS`, `INCOME_AMT`, `SPECIAL_CONSIDERATIONS`, `ASK_AMT`
- **Removed Variables:** 
  - `EIN` and `NAME` (as they are identifiers and not useful for prediction)

### Model Details

- **Architecture:**
  - **Neurons:** 64 in the first layer, 32 in the second, and 16 in the third.
  - **Layers:** Three hidden layers were used.
  - **Activation Functions:** ReLU for hidden layers and Sigmoid for the output layer.
  
- **Performance:**
  - The best accuracy achieved was 72.7%, below the target of 75%.

- **Enhancements Tried:**
  - Increased the number of neurons and layers.
  - Adjusted the architecture to improve model complexity.

## Summary

The model reached only 72.9% accuracy. To achieve better results, consider experimenting with techniques like dropout, batch normalization, or exploring alternative models such as Random Forests which might perform better on this type of structured data.



