# Machine learning of fluid flows using the proper orthogonal decomposition (POD) and the dynamic mode decomposition (DMD) methods

## Introduction

Fluid dynamics has long been challenging due to its inherent high-dimensionality and nonlinear behaviour. Traditional numerical approaches, while effective, often become computationally prohibitive when applied to complex flows, such as turbulent flows past a cylinder. In recent years, data-driven methods have emerged as promising alternatives by extracting the essential dynamics directly from high-fidelity simulation or experimental data. Two techniques, particularly Proper Orthogonal Decomposition (POD) and Dynamic Mode Decomposition (DMD), have gained prominence for their ability to identify coherent structures and predict temporal evolution in fluid flows.

POD, closely related to the singular value decomposition (SVD), decomposes complex flow fields into a set of orthogonal modes ordered by energy content. This enables a reduced-order representation of the flow, capturing the dominant features with a minimal number of modes. On the other hand, DMD builds upon this framework to extract dynamic information from the data, yielding modes associated with specific growth rates and frequencies. These methods facilitate efficient data compression and provide insights into the underlying physics, making them valuable for applications ranging from turbulence modelling to predictive control.

The motivation behind this project lies in harnessing these data-driven techniques to analyze and predict fluid flows. By focusing on a canonical problem of two-dimensional flow past a cylinder at a Reynolds number of 200, we aim to bridge the gap between theoretical developments in machine learning and practical applications in fluid dynamics. This approach reduces the complexity of high-dimensional datasets and paves the way for improved understanding and control of liquid systems.

You can visit this [publication](https://blog.hamzacfa.com/2025/05/machine-learning-of-fluid-flows.html) for the detailed report.
