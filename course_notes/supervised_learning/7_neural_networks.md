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
			- more nodes
			- more layers
			- large numbers
			
- Restriction bias (able to represent)
	- Representational power
	- Set at hypotheses we will consider
	- Perceptron: half spaces 
	- Sigmoid: much more complex not much restriction
	- Functions
		- Boolean: network of threshold-like units
		- Continuous: "connected" no jumps - hidden
		- Arbitrary: stitch together - two hidden
	- Danger of overfitting!
		- Cross validation

- Preference bias
	- Algotirhm's selection of one representation over another
	- What algortihm?
		- Gradient Descent!
		- Initial Weights!
			- Small random values (local minimal, variability)
			- Low "complexity"
			- Simpler explanations
		- Occam's razor: Entities should not be multipled unnecessarily

- Summary
	- Perceptrons: threshold unit
	- Networks can produce any boolean function.
	- Perception rule - finite time for linearly seperable
	- General differentiable rule - back propogation & gradient descent
	- Preference / restriction bias of neural networks
