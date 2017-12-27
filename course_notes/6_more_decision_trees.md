## Decision Trees

- Entropy
  
  > ![equation](http://latex.codecogs.com/gif.latex?entropy=\sum_{i}-p_i\log_2(p_i))
  - Controls how a DT decides where to split the data
  - Definition: measure of impurity in a bunch of examples
- Information Gain
  - Information Gain = entropy (parent) - (weighted average) * entropy (children)
  - Decision tree algorithm: maximize information gain
