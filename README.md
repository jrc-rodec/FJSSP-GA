<a name="Readme"></a>
===================

# Contents #
## Benchmarks ##
Contains 402 benchmark instances used for testing. The benchmarks are organized into their respective sources.
## Code ##
Contains Python code, which allows to run the developed Genetic Algorithm (GA) to optimize selected benchmark problems. The starting point for the code is found in `experiments.py`, where you can select the benchmark instances, define the parameters for the GA and define how many repetitions of the experiment should be executed.
## MILP Model ##
The description of the MILP model used for comparison to assess the performance of the GA can be found in `MILP_Model.pdf`.
## Results ##
A comparison of the achieved results of the GA, the MILP model and previously known results from literature can be found in `all_results.csv`. The file contains the results of each method as well as information about characteristics of the specific benchmark instances.
## Comparison Overview ##
Lastly, there is an overview of the results in comparison to the results provided in the literature:
![Benchmark Overview](https://github.com/jrc-rodec/FJSSP-GA/blob/main/delta_rel_by_benchmark.png)
