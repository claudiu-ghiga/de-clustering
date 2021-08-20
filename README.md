# de-clustering

Density-based clustering algorithm using differential evolution as an optimization engine. Each individual in the population is a (2 * D)-dimensional vector of parameters of a multivariate Gaussian distribution (mean + variance), and the objective is to fit each individual to a local optimum that minimizes the sum of Mahalanobis distances to the instances. A crowding mechanism is used in order to encourage multimodal exploration of the search space.
