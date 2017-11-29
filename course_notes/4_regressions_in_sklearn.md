## Regressions in sklearn

- Minimizing the Sum of Squared Errors
  - ordinary least squares (OLS): used in sklearn LinearRegression.
  - gradient descent
- Sum of Squared Errors(SSE) isn't perfect.
  - If you add more data, SSE will go up.
- R squared
  - "How much of my change in the output (y) is explained by the change in my input (x)."
  - 0.0 < r^2 < 1.0 (line does a good job!)
- Comparing Classification & Regression

  | property | supervised classification | regression
  | --- | --- | --- |
  | output type | discrete (class labels) | continuous (number) |
  | what are you trying to find? | decision boundary | "best fit line" |
  | evaluation | accuracy | "sum of squared error" |
