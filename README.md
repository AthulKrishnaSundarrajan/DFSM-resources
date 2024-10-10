# Derivative Function Surrogate Model (DFSM)
Models that balance accuracy against computational costs are advantageous when designing dynamic systems with optimization studies, as several hundred predictive function evaluations might be necessary to identify the optimal solution. 
Several approaches, such as classic system identification (sys-id) methods and long-short-term memory (LSTM) networks, can be used to construct surrogate models of dynamic systems that can be used in optimization studies.
For dynamic systems, an ordinary differential equation (ODE) describes how the states evolve given the states, inputs, and parameters. In many instances, evaluating this ODE for a given input is often the most expensive operation associated with the study. Creating a surrogate for this ODE is also feasible to reduce the computational cost. Such surrogate models of the dynamic model or the derivative function are called derivative function surrogate models (DFSM).

More details regarding the DFSM approach and its application to floating offshore wind turbines (FOWT) can be found in: [Sundarrajan2023a](https://www.engr.colostate.edu/~drherber/.vendor/bibtexbrowser/bibtexbrowser.php?key=Sundarrajan2023a&bib=default)

The following presentation explores the trade-off betwen classic sys-id methods, and LSTM networks for creating surrogate models for control optimization of FOWT: [Sundarrajan2024c](https://www.engr.colostate.edu/~drherber/.vendor/bibtexbrowser/bibtexbrowser.php?key=Sundarrajan2024c&bib=default)

An example of using the DFSM for closed-loop control simulation of FOWT can be found in: [Example_19](https://github.com/AthulKrishnaSundarrajan/WEIS/tree/ctopt-debug/examples/19_DFSM)

Feel free to reach out to [Athul.Sundarrajan@colostate.edu](mailto:Athul.Sundarrajan@colostate.edu) or [Daniel.Herber@colostate.edu](mailto:Daniel.Herber@colostate.edu) for additional information and references.
