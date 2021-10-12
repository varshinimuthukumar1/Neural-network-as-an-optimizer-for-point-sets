# Neural-network-as-an-optimizer-for-point-sets

This is an experiment to achieve resampling of point sets in 2D using a neural network.  The network is trained in an unsupervised way, with only the spectral characteristic curve.  The training set is initialized with random Gaussian data, and using a simple MLP the point set can be moved towards Poisson distribution.

However, this is not ideal since there is always a bias towards learning a same representation and the output lacks variability and randomness.  


![image](https://user-images.githubusercontent.com/60971850/137001370-779166b7-633d-4b28-bb0c-7a12412ccca0.png)

