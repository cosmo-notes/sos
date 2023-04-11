# Simulation of Systems using computational algorithms

Virtually all modeling projects turn at one point or another to simulations. These are computational algorithms performing a deterministic or stochastic set of rules to track the potential evolution of a model. These are brute force approaches, as running a simulation can be more time consuming then solving its expected output mathematically. However, simulations can be useful at multiple points of a modeling projects, especially when they leverage clever algorithmic tricks.

Simulations of a system can be an easy way to explore a model before committing time to developing a mathematical approach to its analysis. Are the simple rules you design able to produce the interesting phenomenon you care about? What better way to find out than to actually apply the rules? Simulations can also be useful when validating your mathematical framework or testing different mathematical approximations. Finally, simulations can be used to track the outputs of a particularly complicated model or of an expansive subroutine of a larger model. With too many rules and types of moving parts, agent-based models often require direct simulations.

Here is an additional reference to provide more details and more methods than covered in this tutorial:
- **_Stochastic simulation algorithms for computational systems biology: Exact, approximate, and hybrid methods_** {cite}`simoni2019stochastic`. It is important to note that many of the simulation approaches used in complexity come from systems biology and the study of complex chemical systems. These communities routinely deal with very large populations of systems parts undergoing a complex set of spatial, stochastic, and higher-order interactions.

Our main goal is to provide a tutorial on the key concepts behind the most common simulation approaches in the study of complex systems. As applications, we will rely on classic models from complexity such as birth-death processes, the game of life, swarming dynamics, and contagion dynamics on networks.

## Table of content
```{tableofcontents}
```

## References
```{bibliography}
```
