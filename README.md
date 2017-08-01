![](doc/userGuide/source/images/logo.png)

This is the development site for MPCPy, the python-based open-source platform for model predictive control in buildings.

## General
MPCPy is a python package that facilitates the testing and implementation of occupant-integrated model predictive control (MPC) for building systems.  The package focuses on the use of data-driven, simplified physical or statistical models to predict building performance and optimize control.  Four main modules contain object classes to import data, interact with real or emulated systems, estimate and validate data-driven models, and optimize control input.

## Third Party Software
While MPCPy provides an integration platform, it relies on free, open-source, third-party software packages for model implementation, simulators, parameter estimation algorithms, and optimization solvers.  This includes python packages for scripting and data manipulation as well as other more comprehensive software packages for specific purposes.  In particular, modeling and optimization for physical systems rely heavily on the Modelica language specification (https://www.modelica.org/) and FMI standard (http://fmi-standard.org/) in order to leverage model library and tool development on these standards occurring elsewhere within the building and other industries.

## Contributing
Research has shown that MPC can address emerging control challenges faced by buildings.  However, there exists no standard practice or methods for implementing MPC in buildings.  Implementation is defined here as model structure, complexity, and training methods, data resolution and amount, optimization problem structure and algorithm, and transfer of optimal control solution to real building control.  In fact, different applications likely require different implementations.  Therefore, we aim for MPCPy to be flexible enough to accommodate different and new approaches to MPC in buildings as research approaches a consensus on best-practice methods.

If you are interested in contributing to this project:

- You are welcome to report any issues in [Issues](https://github.com/lbl-srg/MPCPy/issues).
- You are welcome to make a contribution by following the steps outlined on the [Contribution Workflow](https://github.com/lbl-srg/MPCPy/wiki/Contribution-Workflow) page.

## Getting Started
For installation and an introductory tutorial, see Section 2 of the [User Guide](https://github.com/lbl-srg/MPCPy/tree/master/doc/userGuide).  

Then, take a look at the ipython notebook examples in the ``examples`` directory.

## License
MPCPy is available under the following open-source [license](https://github.com/lbl-srg/MPCPy/blob/master/license.txt).
