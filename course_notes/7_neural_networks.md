## Neural Networks

- Artificial Nueral Networks

  - > ![equation](http://latex.codecogs.com/gif.latex?\sum_{i}-x_iw_i\geq\Theta)

- Perceptron Unit
  - AND, OR, NOT: expressible as perceptron units, can represent anything.
  
- Perceptron Training
  - Given examples, find weights that map inputs to outputs
    - Perceptron rule (threadhold)
    - Gradient descent / delta rule (unthreadholded)

- Comparison of learning rules
  - Perceptron: guarantee
    - finite convergence
    - linear seperability

  - Gradient descent: calculus
    - robust
    - converge local optimal
    - Why not do gradient descent on y-hat? non-differentiable
    
- Sigmoid - Differentiable threshold

- Neural Network
  - Backpropagation: Computationally beneficial organization of the chain rule.
  - Many local optima
  - Optimizing weights
    - Gradient descent
    - Advanced methods
      - momentum
      - higher order derivatives
      - randomized optimization
      - penalty for "complexity"
        - regression "overfitting"
        - large tree "overfitting"
        
