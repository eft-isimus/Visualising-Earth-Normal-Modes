The jupyter notebook provided here contains modular Python code for visualising the Earth's normal modes. There are functions for computing the displacement of the surface under normal modes of different orders, as well as functions that utilise the Mayavi package to visualise the motion of the Earth. \href{https://github.com/geodynamics/mineos}{Mineos} is a software program that can be used to compute the displacements of each point along a one-dimensional Earth model. A text file is provided which explains how to install and use Mineos, the output of which can then be used in the Jupyter notebook to visualise the motion of the entire Earth instead of just the surface. 

The following python packages are required:
- NumPy
- Matplotlib
- Mayavi

Mineos is easier to install in a Linux environment, and is required for animations showing the motion of the entire Earth, but surface animations can be created without it. We suggest checking out the Mineos manual found in the \href{https://github.com/geodynamics/mineos}{Mineos Github repo} for help regarding installation and usage. 
