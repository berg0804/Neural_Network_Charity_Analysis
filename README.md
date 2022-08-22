# Neural_Network_Charity_Analysis
## Overview
The purpose of this project is help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. A provided dataset with more than 34,000 organizations will be analzed with machine learning and neural networks.
## Results
- What variable(s) are considered the target(s) for your model?
  - If the target is marked as successfully funded by Alphabet Soup.
- What variable(s) are considered to be the features for your model?
  - The feature is the IS_SUCCESSFUL column.
- What variable(s) are neither targets nor features, and should be removed from the input data?
  - EIN and NAME are neither targets nor features and were removed.
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - There are 4 layers with 120, 80, 40, and 20 neurons respectively. The relu and sigmoid activations were used.
![Screen Shot 2022-08-21 at 8 42 34 PM](https://user-images.githubusercontent.com/67160240/185818729-96061bd6-2261-4d0b-b645-1f43759fecb5.png)
- Were you able to achieve the target model performance?
  - The target was 75% accuracy howver the model produced 47% accuracy.
- What steps did you take to try and increase model performance?
  - Removing columns, adjusting neurons, and changing activation models.
## Summary
The chosen activations did not meet the accuracy goal of 75%. Different iterations of neurons, layers, and activations could be possibly chosen to improve accuracy. Additioanly a random forest classifier can be tried as it handles outliers well.
