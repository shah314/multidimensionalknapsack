<h1>Genetic Algorithm for the 0/1 Multidimensional Knapsack Problem</h1>

<a href="https://doi.org/10.5281/zenodo.3344947"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.3344947.svg" alt="DOI"></a>

<p>The 0/1 multidimensional knapsack problem is the 0/1 knapsack problem with m constraints which makes it difficult to solve using traditional methods like dynamic programming or branch and bound algorithms. We present a genetic algorithm for the multidimensional knapsack problem with Java code that is able to solve publicly available instances in a very short computational duration. Our algorithm uses iteratively computed Lagrangian multipliers as constraint weights to augment the greedy algorithm for the multidimensional knapsack problem and uses that information in a greedy crossover in a genetic algorithm. The algorithm uses several other hyperparameters which can be set in the code to control convergence. Our algorithm improves upon the algorithm by Chu and Beasley in that it converges to optimum or near optimum solutions much faster.</p>

<h3>References</h3>

[1] Chu, Paul C., and John E. Beasley. "A genetic algorithm for the multidimensional knapsack problem." Journal of heuristics 4.1 (1998): 63-86.
[2] Shah, Shalin. "Genetic Algorithm for a class of Knapsack Problems." arXiv preprint arXiv:1903.03494 (2019).
[3] http://people.brunel.ac.uk/~mastjjb/jeb/orlib/files/mknap2.txt
[4] https://github.com/shah314/gamultiknapsack
[5] “A Monte-Carlo study of genetic algorithm initial population generation methods”, R. Hill, Proceedings of the 31st conference on winter simulation: Simulation---a bridge to the future - Volume 1, 1999, 543--547 (1999)
[6] “Optimization by simulated annealing”, S. Kirkpatrick, Science, Number 4598, 13 May 1983, volume 220, 4598, 671--680 (1983) 
[7] “Theoretical and Numerical Constraint Handling Techniques used with Evolutionary Algorithms: A Survey of the State of the Art”, C. Coello, Computer Methods in Applied Mechanics and Engineering, 191 (11--12), 1245-1287, January 2002 (2002)
