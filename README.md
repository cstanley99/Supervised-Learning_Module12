# Supervised-Learning_Module12

The purpose of this exercise is to attempt to build a model that can determine the creditworthiness of borrowers.  The data provided is from a peer-to-peer lending services company and contains metrics on over 77,000 loans.  Because healthy loans greatly outnumber risky loans, the classification is imbalanced.  There are 75,000 healthly loans versus only 2500 risky loans.  The analysis will include both a logistical regression model with the the original data and model with resampled data using oversampling.

## Results

Machine Learning model 1 (original data)

   *accuracy = 0.9520479254722232
  
   *precision = 1.0 healthy and 0.85 risky
  
   *recall = 0.99 healthy .91 risky
  
  
Machine Learning model 2 (oversampled)

  *accuracy = 0.9936781215845847
  
  *precision = 1.0 healthy and 0.84 risky
  
  *recall = 0.99 healthy and 0.99 risky
  
## Summary
  
Model 2, fit with the oversampled data to overcome the inherent imbalance, is clearly the best model.   When looking at the risky loans, it's accuarcy and recall scores are superior to Model 1 and the precision is about even for both models.
