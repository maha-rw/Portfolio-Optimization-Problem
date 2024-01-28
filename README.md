# Portfolio-Optimization-Problem
The project involves constructing an investment portfolio by optimizing asset allocation. The goal is to maximize expected return while managing risk through variance and covariance. Constraints include a budget constraint and limits on asset weights. The objective is to create an efficient portfolio.


This experiment compares the performance of the Genetic Algorithm (GA) and the Local Search algorithm with random restarts for portfolio optimization. The objective is to maximize returns while managing risk.

### Local Search Algorithm:
- Executed five times with random starts for exploration.

- Termination criterion: 10,000 fitness evaluations with reset mechanism.
  
- Fitness value calculated based on portfolio return and risk rate.

- Neighbor solutions generated iteratively, and the algorithm updates the current solution if the fitness improves.

- Performance evaluated using fitness values; the best solution is selected based on the highest fitness value.


### Genetic Algorithm:
- Executed five times with different random seeds.
  
- Termination criterion: 10,000 fitness evaluations.
  
- Random restarts crucial for escaping local optima and exploring diverse solution spaces.
  
- Fine-tuned parameters (population size, mutation rate, crossover strategy) improved performance.
  
- Selection, crossover, mutation, and replacement operations applied iteratively.
  
- Solutions and fitness values stored in GA_results; the best solution and fitness value identified.

  
### Results:
- Genetic Algorithm outperformed Local Search in terms of higher fitness values.
  
- Both algorithms involve randomness, contributing to variability in results.
  
- Choice between algorithms depends on problem characteristics, computational resources, and desired exploration-exploitation balance.

  
### Conclusion:
The Genetic Algorithm demonstrated robust performance, exploring diverse solution spaces and consistently achieving higher fitness values. Random restarts and parameter fine-tuning contributed to its success. The Local Search algorithm effectively found optimal or near-optimal solutions, highlighting the importance of randomness and continuous exploration. Overall, the Genetic Algorithm showcased efficacy in navigating complex solution spaces, emphasizing the versatility of optimization tools for portfolio management. The choice between algorithms depends on specific problem characteristics and computational considerations.


