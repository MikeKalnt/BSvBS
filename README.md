# Official implementation: "Energy-aware Scheduling of Virtualized Base Stations in O-RAN with Online Learning"
This code sample includes the implementation of our algorithm, BSvBS, which is used for scheduling virtualized Base Stations (vBS) in Open-Radio Access Networks (O-RAN).

Paper: https://arxiv.org/abs/2208.09956

Authored by: Michail Kalntis, George Iosifidis

## Abstract
> The design of Open Radio Access Network (O-RAN) compliant systems for configuring the virtualized Base Stations (vBSs) is of paramount importance for network operators. This task is challenging since optimizing the vBS scheduling procedure requires knowledge of parameters, which are erratic and demanding to obtain in advance. In this paper, we propose an online learning algorithm for balancing the performance and energy consumption of a vBS. This algorithm provides performance guarantees under unforeseeable conditions, such as non-stationary traffic and network state, and is oblivious to the vBS operation profile. We study the problem in its most general form and we prove that the proposed technique achieves sub-linear regret (i.e., zero average optimality gap) even in a fast-changing environment. By using real-world data and various trace-driven evaluations, our findings indicate savings of up to 74.3% in the power consumption of a vBS in comparison with state-of-the-art benchmarks.

## Requirements
This project has been developed and tested in Python 3.8.10 and requires the following libraries:

- NumPy
- Matplotlib
- Itertools


## Licence 
Distributed under the MIT License. See [LICENCE](https://github.com/MikeKalnt/BSvBS/blob/main/LICENSE) for more information.
