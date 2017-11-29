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
