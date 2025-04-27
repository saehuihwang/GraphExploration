# CHI 2025 LBW
### Title: Computational Modeling of Non-Visual Vibrotactile Touchscreen Exploration
[link](https://dl.acm.org/doi/full/10.1145/3706599.3719851)
#### Abstract
Using vibration feedback on a touchscreen is a promising method to provide blind and low-vision (BLV) users access to graphical content. While prior studies have explored the design space of vibrotactile rendering of graphics, findings do not generalize to complex shapes, and comprehensive standards for vibrotactile graphics comparable to those for tactile graphics are yet to be defined. To address this gap, we present a computational model for non-visual vibrotactile touchscreen exploration using a partially observable Markov decision process (POMDP) framework. Preliminary simulations of a triangle-tracing task demonstrate that empirically observed exploration strategies, such as circling or crossing around a point, emerge as adaptive behaviors under this framework. The model can further incorporate factors such as memory limitations and observation uncertainty, providing a new approach for analyzing exploration behaviors influenced by environmental and user-specific variables. This framework introduces a tool to understand non-visual exploration strategies and inform vibrotactile graphics design.

#### GraphExploration.jl
A Julia implementation for graph-based exploration memory models.
