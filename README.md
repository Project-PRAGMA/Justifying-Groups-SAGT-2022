This folder contains the code for reproducing the results presented in the paper "Justifying Groups in Multiwinner Approval Voting"

**Important:** This code builds upon code contributed by Andrzej Kaczmarczyk (https://github.com/droodev/mulwin-just-pub/releases/tag/v0.1.0_MIT_license). More specifically, our code uses the files "baseProgram", "distributions", and "isxJRChecker". 

In order to recreate the results of the experiments on the "Empirical Evaluation of Theorem 3.1", run 'main_exp1.py' with python3. 
For the experiments on the "Performance of the two Greedy algorithms", run 'main_exp2.py' with python3. For the latter experiments a gurobi license is required (>=academic license, free trial does not suffice). For both experiments, running the code can take a few hours. 

Used packages:
- pandas 1.2.4
- numpy 1.20.1
- matplotlib 3.3.4
- gurobipy 9.1.2
- pulp  2.4
- math 
- random
