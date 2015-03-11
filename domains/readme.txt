Provides the resources for all 3 domains extending the HyFlex benchmark set:
- kp: 0-1 Knapsack Problem
- qap: Quadratic Assignment Problem
- mac: Max Cut Problem

For each of these domains a jar file is provided, containing their respective binaries, as well as a brief description of the problem domain and heuristic set.

- hyflex_ext.jar, a jar file packaging all 3 domains.

To use the domains, simply add one of the jar files to the classpath of your problem, alongside with the original chesc.jar (containing HyFlex itself), which can be found at http://www.asap.cs.nott.ac.uk/external/chesc2011/
and create an instance of the desired ProblemDomain class:
- kp: KnapsackProblem.class 
- qap: QAP.class 
- mac: MaxCut.class 

Use this instance, as you would use any of the 6 original HyFlex domains.

If you do use any of these resources for your research, we kindly ask you to acknowledge this, by citing the following article:

Adriaensen, Steven, Gabriela Ochoa, and Ann Nowé. "A Benchmark Set Extension and Comparative Study for the HyFlex Framework." Evolutionary Computation (CEC), 2015 IEEE Congress on. IEEE, 2015.

@inproceedings{adriaensen2015benchmark,
  title={A Benchmark Set Extension and Comparative Study for the HyFlex Framework},
  author={Adriaensen, Steven and Ochoa, Gabriela and Now{\'e}, Ann},
  booktitle={Evolutionary Computation (CEC), 2015 IEEE Congress on},
  year={2015},
  organization={IEEE}
}