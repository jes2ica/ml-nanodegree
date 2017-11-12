## Machine Learning Foundations
### Evaluation Metrics
- Confusion Matrix
- Accuracy
  ```
  from sklearn.metrics import accuracy_score
  accuracy_score (y_true, y_pred)
  ```
- Precision
- Recall
- F1 Score

### Detecting Errors
- Type of Errors
  - Underfitting: Bad on training set; Bad on testing set. 
  - Overfitting: Good on training set; Bad on testing set. 
- Cross Validation

## Supervised Learning
### Errors
- Training data has errors, not modeling f, but f + e:
  - sensor error
  - maliciously: being gien bad data
  - transcription error
  - unmodeled influences
### Cross Validation
- Use a model that is complex enough to fit the data without causing problems on the test set.
### Other Input Spaces
- scalar input, continuous
- vector input, continuous
- vector or scalar input, discrete
### Conclusion
- historical facts
- model selection and under/over fitting
- cross validation
- linear, polynomial regression
- best constant in terms of squared error! mean
- representation for regression
