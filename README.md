# venture_funding_with_deep_learning
# Overview

This is a Jupyter notebook whose purpose is create a model that predicts whether Alphabet Soup 

funding applicants will be successful, with a binary classification model using a deep neural 

network.

consists of three technical deliverables:

Preprocess data for a neural network model.

Use the model-fit-predict pattern to compile and evaluate a binary classification model.

Optimize the model.

![venture_funding_with_deep_learning](images/labels_and_features.png)
![venture_funding_with_deep_learning](images/Balance_and_splitting.png)


---

## Technologies

This setup assumes you already have conda installed.

This project leverages python 3.7 with the following packages:

![venture_funding_with_deep_learning](images/imports.png)


---

## Results

* Machine Learning Model 1:
  
  * I found that the model 1 wich include the original data is 95% of accuracy
  
  * With a Precision of 100% on the "0" (healthy loans), and 85% on the "1" (risky loans)
  
  * The Recall scores where for "0" 99% and for "1" was of 91%.



* Machine Learning Model 2:
  
  * The Model 2 wich include the resampled data is 99% of accuracy
  
  * With a Precision of 100% on the "0" (healthy loans), and 84% on the "1" (risky loans)
  
  * The Recall scores where for "0" 99% and for "1" was of 99%.
  
---

## Summary

* The model number 2 with the resampled data seems to be the one that performs better due to the diference in accuracy with 99% vs 95% of the model 1., Even when the precision on the model 2 is lower 1% in "1" but in the recall scores the model 2 was better with 8% higher difference against the moldel 1  

* The performance in the problem to solve was better in model 2 since the improvement was more noticeable on the "1" which is the more important factor to predict to be able to detect risky loans 




---
## Contributors

Israel Fernandez

---
