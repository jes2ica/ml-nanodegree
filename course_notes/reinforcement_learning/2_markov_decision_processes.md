## Markov Decision Processes
### Decision Making & Reinforcement Learning
- Supervised Learning: y = f(x) => functional approx
- Unsupervised Learning: f(x) => clusters description
- Reinforcement Learning: y = f(x), z
### Markov Decision Processes
`only present matters!`
- STATES: S
- MODEL: T(s, a, s') ~ Pr(s'|s, a)
- ACTIONS: A(s), A
- REWARD: R(s), R(s, a), R(s, a, s')
- POLICY: 
  - π(s) -> a <s, a>, <s, a>
  - π*(s) -> a <s, a, r>, <s, a, r>
### MDPs: More About Rewards
- delayed reward
- minor changes matter
### Sequences of Rewards: Assumptions
- Infinite horizons
- Utility of sequences
- if U(s0, s1, ...) > U(s0, s1', ...) => then U(s1, s2, ...) > U(s1', s2', ...)
- U(s0, s1, s2, ...) = sum(R(st)) = sum(γ^t * R(st)) <= sum(γ^t * R(max)) = R(max) / 1 - γ  (0 <= γ < 1)
- discounted -> geometric
- infinite -> finite
### Policies
- start w/ arbitrary utilities
- update utilities based on neighbors
- repeat until convergence
### Finding Policies
- start w/ π0 <- guess
- evaluate: given πt calculate Ut 
- improve
### Summary
- MDPs (states, rewards, actions, transitions)
- policies
- value functions (utilities -> long term!)
- discounting ? finite, infinite
- stationaly
- Bellman (policy iteration, value iteration)
