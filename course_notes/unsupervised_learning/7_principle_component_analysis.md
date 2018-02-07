## PCA
- How to determine the principle component?
  - variance: technical term in stats - roughly the "spread" of a data distribution (similar to standard deviation).
  - principle component of a dataset is the direction that has the largest variance
- Maximal variance and information loss
  - projection onto direction of maximal variance minimizes distance 
  from old (higher-dimensional) data point to its new transformed value
- Review / Definition of PCA
  - systematized way to tranform input features into priciple components
  - use principle components as new features
  - PCs are directions in data that maximize variance (minimize information loss) when you project/compress down onto them
  - more variance of data along a PC, higher that PC is ranked
  - most variance / most information -> first PC; second most variance (without overlapping with the first PC) -> second PC
  - max no. of PCs = no. of input features
  
