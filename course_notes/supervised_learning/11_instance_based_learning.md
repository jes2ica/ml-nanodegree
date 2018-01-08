### Instance Based Learning
- f(x) = lookup(x)
- Pros
  - remembers
  - fast
  - simple
- Cons
  - generalization? No
  - overfitting? Yes
- k-NN
  - Manhattan Distance: d(i,j)=|X1-X2|+|Y1-Y2|
  - Manhattan Distance: d(i,j)=|X1-X2|+|Y1-Y2|

Compute neighbors
  
Given n sorted data points...

\- | Running Time | Space
------------ | ------------- | -------------
1-NN | Learning: 1; Query: log N | Learning: n; Query: 1
k-NN | Learning: 1; Query: log N + k| Learning: n; Query: 1
linear regression | Learning: n; Query: 1| Learning: 1; Query: 1

- k-NN: lazy
- linear regression: eager

- k-NN Bias
  - Preference bias: our belief about what makes a good hypothesis
  - locality -> near points are similar
  - smoothness -> averaging
  - all features matter equally
  
- Curse of Dimensionality: As the number of features or demensions grows, the amount of data we need to generalize accurately grows exponentially.
- Some other stuff
  - d(x, q) = euclidean, manhattan (weighted)
  - k = n
    - weighted average
    - locally weighted regression

- Summary
  - instance based learning
  - lazy vs eager learning
  - k-nn
  - nearest neighbor: similarity distance
  - classification vs regression
  - averaging
  - locally weighted $x regression
  - curses O(2^d)
